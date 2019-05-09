---
date: 2019-05-09T10:51:07Z
title: "jx delete addon istio"
slug: jx_delete_addon_istio
url: /commands/jx_delete_addon_istio/
---
## jx delete addon istio

Deletes the Istio addon

### Synopsis

Deletes the Istio addon

```
jx delete addon istio [flags]
```

### Examples

```
  # Deletes the Istio addon
  jx delete addon istio
```

### Options

```
  -h, --help               help for istio
  -n, --namespace string   The Namespace to delete from (default "istio-system")
  -p, --purge              Removes the release name from helm so it can be reused again (default true)
  -r, --release string     The chart release name (default "istio")
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx delete addon](/commands/jx_delete_addon/)	 - Deletes one or more addons

###### Auto generated by spf13/cobra on 9-May-2019