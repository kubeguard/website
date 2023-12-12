---
title: Guard Get Webhook-Config
menu:
  docs_v0.16.1:
    identifier: guard-get-webhook-config
    name: Guard Get Webhook-Config
    parent: reference
product_name: guard
menu_name: docs_v0.16.1
section_menu_id: reference
info:
  version: v0.16.1
---

## guard get webhook-config

Prints authentication token webhook config file

```
guard get webhook-config [flags]
```

### Options

```
      --addr string           Address (host:port) of guard server. (default "10.96.10.96:443")
  -h, --help                  help for webhook-config
      --mode string           Mode to generate config, Supported mode: authn, authz (default "authn")
  -o, --organization string   Name of Organization (Azure/Github/Gitlab/Google/Ldap/Token-Auth).
      --pki-dir string        Path to directory where pki files are stored. (default "/Users/tamal/.guard")
```

### SEE ALSO

* [guard get](/docs/v0.16.1/reference/guard_get)	 - Get PKI

