---
title: Welcome | Guard
description: Welcome to Guard
menu:
  docs_0.1.0:
    identifier: readme-guard
    name: Readme
    parent: welcome
    weight: -1
product_name: guard
menu_name: docs_0.1.0
section_menu_id: welcome
url: /docs/0.1.0/welcome/
aliases:
- /docs/0.1.0/
- /docs/0.1.0/README/
info:
  version: 0.1.0
---

# Guard

Guard by AppsCode is a [Kubernetes Webhook Authentication](https://kubernetes.io/docs/admin/authentication/#webhook-token-authentication) server. Using guard, you can log into your Kubernetes cluster using your Github or Google authentication token. Guard also sets authenticated user's groups to his Github teams or Google groups. This allows cluster administrator to setup RBAC rules based on membership in Github teams or Google groups.

From here you can learn all about Guard's architecture and how to deploy and use Guard.

- [Concepts](/docs/0.1.0/concepts/). Concepts explain some significant aspect of Guard. This is where you can learn about what Guard does and how it does it.

- [Setup](/docs/0.1.0/setup/). Setup contains instructions for installing
  the Guard in various cloud providers.

- [Guides](/docs/0.1.0/guides/). Guides show you how to perform tasks with Guard.

- [Reference](/docs/0.1.0/reference/). Detailed exhaustive lists of
command-line Options, configuration Options, API definitions, and procedures.

We're always looking for help improving our documentation, so please don't hesitate to [file an issue](https://github.com/appscode/guard/issues/new) if you see some problem. Or better yet, submit your own [contributions](/docs/0.1.0/CONTRIBUTING) to help
make our docs better.

---

**Guard binaries collects anonymous usage statistics to help us learn how the software is being used and how we can improve it. To disable stats collection, run the operator with the flag** `--analytics=false`.

---
