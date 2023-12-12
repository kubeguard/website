---
title: Welcome | Guard
description: Welcome to Guard
menu:
  docs_v0.8.1:
    identifier: readme-guard
    name: Readme
    parent: welcome
    weight: -1
product_name: guard
menu_name: docs_v0.8.1
section_menu_id: welcome
url: /docs/v0.8.1/welcome/
aliases:
- /docs/v0.8.1/
- /docs/v0.8.1/README/
info:
  version: v0.8.1
---

# Guard

Guard by AppsCode is a [Kubernetes Webhook Authentication](https://kubernetes.io/docs/admin/authentication/#webhook-token-authentication) server. Using guard, you can log into your Kubernetes cluster using a Github or Google authentication token. Guard also sets authenticated user's groups to their Github teams or Google groups. This allows cluster administrators to setup RBAC rules based on membership in Github teams or Google groups.

From here you can learn all about Guard's architecture and how to deploy and use Guard.

- [Concepts](/docs/v0.8.1/concepts/). Concepts explain some significant aspects of Guard. This is where you can learn about what Guard does and how it does it.

- [Setup](/docs/v0.8.1/setup/). Setup contains instructions for installing Guard using various Kubernetes installers.

- [Guides](/docs/v0.8.1/guides/). Guides show you how to perform tasks with Guard.

- [Reference](/docs/v0.8.1/reference/). Detailed exhaustive lists of
command-line Options, configuration Options, API definitions, and procedures.

We're always looking for help on improving our documentation, so please don't hesitate to [file an issue](https://go.kubeguard.dev/guard/issues/new) if you see some problem. Or better yet, submit your own [contributions](/docs/v0.8.1/CONTRIBUTING) to help
make our docs better.

---

**Guard binaries collects anonymous usage statistics to help us learn how the software is being used and how we can improve it. To disable stats collection, run the operator with the flag** `--analytics=false`.

---
