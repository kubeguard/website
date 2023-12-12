---
title: Guard Get Webhook-Config
menu:
  docs_v0.6.1:
    identifier: guard-get-webhook-config
    name: Guard Get Webhook-Config
    parent: reference
product_name: guard
menu_name: docs_v0.6.1
section_menu_id: reference
info:
  version: v0.6.1
---

## guard get webhook-config

Prints authentication token webhook config file

### Synopsis

Prints authentication token webhook config file

```
guard get webhook-config [flags]
```

### Options

```
      --addr string           Address (host:port) of guard server. (default "10.96.10.96:443")
  -h, --help                  help for webhook-config
  -o, --organization string   Name of Organization (Azure/Github/Gitlab/Google/Ldap/Token-Auth).
      --pki-dir string        Path to directory where pki files are stored. (default "$HOME/.guard")
      --mode                  Mode to generate config, Supported mode: authn,authz (default "authn")
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

* [guard get](/docs/v0.6.1/reference/guard_get)	 - Get PKI

