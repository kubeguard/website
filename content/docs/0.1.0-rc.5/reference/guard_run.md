---
title: Guard Run
menu:
  docs_0.1.0-rc.5:
    identifier: guard-run
    name: Guard Run
    parent: reference
product_name: guard
menu_name: docs_0.1.0-rc.5
section_menu_id: reference
info:
  version: 0.1.0-rc.5
---

## guard run

Run server

### Synopsis


Run server

```
guard run [flags]
```

### Options

```
      --ca-cert-file string   File containing CA certificate
      --cert-file string      File container server TLS certificate
  -h, --help                  help for run
      --key-file string       File containing server TLS private key
      --ops-addr string       Address to listen on for web interface and telemetry. (default ":56790")
      --web-address string    Http server address (default ":9844")
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --analytics                        Send analytical events to Google Guard (default true)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [guard](/docs/0.1.0-rc.5/reference/guard)	 - Guard by AppsCode - Kubernetes Authentication WebHook Server

