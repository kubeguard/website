---
title: Amazon EKS | Guard
description: Authenticate into Amazon EKS cluster
menu:
  docs_v0.6.1:
    identifier: amazon-eks
    parent: authenticator-guides
    name: EKS
    weight: 45
product_name: guard
menu_name: docs_v0.6.1
section_menu_id: guides
info:
  version: v0.6.1
---

# Amazon EKS

Guard installation guide can be found [here](/docs/v0.6.1/setup/install). Install the Guard on your system by following `Install Guard as CLI`.

### Configure Kubectl

To use EKS cluster with Guard, you have to install AWS CLI on your system. Follow [Configuring the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html) in the AWS command Line Interface User Guide.

Guard uses the same credential that are returned with the following command.

```console
$ aws sts get-caller-identity
```

Open `~/.kube/config` file with your favourite editor and copy the following code.

```console
apiVersion: v1
clusters:
- cluster:
    server: <endpoint-url>
    certificate-authority-data: <base64-encoded-ca-cert>
  name: kubernetes
contexts:
- context:
    cluster: kubernetes
    user: aws
  name: aws
current-context: aws
kind: Config
preferences: {}
users:
- name: aws
  user:
    exec:
      apiVersion: client.authentication.k8s.io/v1alpha1
      command: guard
      args:
        - "login"
        - "-k"
        - "<cluster-name>"
        - "-p"
        -  "eks"
```

Here,
1. Replace the `<endpoint-url>` with endpoint URL, which can be retrieved by following command
```console
$ aws eks describe-cluster --name <cluster-name>  --query cluster.endpoint
```

2. Replace the `<base64-encoded-ca-cert>` with the certificate authority data, which can be retrieved by following command
```console
$ aws eks describe-cluster --name <cluster-name>  --query cluster.certificateAuthority.data
```

To test the configuration run
```console
$ kubectl get pods --all-namespaces
```