---
date: 2019-10-09T13:03:39Z
title: "jx upgrade cluster"
slug: jx_upgrade_cluster
url: /commands/jx_upgrade_cluster/
---
## jx upgrade cluster

Upgrades the Kubernetes master to the specified version

### Synopsis

Upgrades the Jenkins X Kubernetes master to the specified version

```
jx upgrade cluster [flags]
```

### Examples

```
  # Upgrades the Jenkins X Cluster tools
  jx upgrade cluster
```

### Options

```
  -c, --cluster-name string   The specific cluster to upgrade
  -h, --help                  help for cluster
  -v, --version string        The specific version to upgrade to
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx upgrade](/commands/jx_upgrade/)	 - Upgrades a resource

###### Auto generated by spf13/cobra on 9-Oct-2019
