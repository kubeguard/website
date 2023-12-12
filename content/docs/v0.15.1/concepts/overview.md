---
title: Overview | Guard
menu:
  docs_v0.15.1:
    identifier: overview-concepts
    name: Overview
    parent: concepts
    weight: 10
product_name: guard
menu_name: docs_v0.15.1
section_menu_id: concepts
info:
  version: v0.15.1
---

# Guard

 Guard by AppsCode is a [Kubernetes Webhook Authentication](https://kubernetes.io/docs/admin/authentication/#webhook-token-authentication) server. Using guard, you can log into your Kubernetes cluster using your Github or Google authentication token. Guard also sets authenticated user's groups to his Github teams or Google groups. This allows cluster administrator to setup RBAC rules based on membership in Github teams or Google groups.
