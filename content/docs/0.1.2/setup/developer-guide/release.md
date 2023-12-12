---
title: Release | Guard
description: Guard Release
menu:
  docs_0.1.2:
    identifier: release
    name: Release Process
    parent: developer-guide
    weight: 15
product_name: guard
menu_name: docs_0.1.2
section_menu_id: setup
info:
  version: 0.1.2
---

# Release Process

The following steps must be done from a Linux x64 bit machine.

- Do a global replacement of tags so that docs point to the next release.
- Push changes to the `release-x` branch and apply new tag.
- Push all the changes to remote repo.
- Build and push guard docker image:

```console
cd ~/go/src/github.com/appscode/guard
./hack/release.sh
```

- Now, update the release notes in Github. See previous release notes to get an idea what to include there.
