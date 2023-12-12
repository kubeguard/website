---
title: Guard Login
menu:
  docs_v0.5.0-rc.1:
    identifier: guard-login
    name: Guard Login
    parent: reference
product_name: guard
menu_name: docs_v0.5.0-rc.1
section_menu_id: reference
info:
  version: v0.5.0-rc.1
---

## guard login

Kubectl credential plugin

### Synopsis

Kubectl credential plugin. Visit here for more info: https://kubernetes.io/docs/reference/access-authn-authz/authentication/#client-go-credential-plugins

```
guard login [flags]
```

### Options

```
  -k, --cluster string    Name of cluster
  -h, --help              help for login
  -p, --provider string   Name of cloud provider
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --analytics                        Send analytical events to Google Guard (default true)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default true)
      --stderrthreshold severity         logs at or above this threshold go to stderr
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [guard](/docs/v0.5.0-rc.1/reference/guard)	 - Guard by AppsCode - Kubernetes Authentication WebHook Server

