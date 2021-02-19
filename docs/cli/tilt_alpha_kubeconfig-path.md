---
title: Tilt CLI Reference
layout: docs
hideEditButton: true
---
## tilt alpha kubeconfig-path

Prints out a path to a KUBECONFIG for querying the Tilt apiserver

```
tilt alpha kubeconfig-path [flags]
```

### Examples

```
KUBECONFIG=$(tilt alpha kubeconfig-path) kubectl api-resources
```

### Options

```
  -h, --help          help for kubeconfig-path
      --host string   Host for the Tilt HTTP server. Only necessary if you started Tilt with --host. Overrides TILT_HOST env variable. (default "localhost")
      --port int      Port for the Tilt HTTP server. Only necessary if you started Tilt with --port. Overrides TILT_PORT env variable. (default 10350)
```

### Options inherited from parent commands

```
  -d, --debug                          Enable debug logging
      --klog int                       Enable Kubernetes API logging. Uses klog v-levels (0-4 are debug logs, 5-9 are tracing logs)
      --log-flush-frequency duration   Maximum number of seconds between log flushes (default 5s)
  -v, --verbose                        Enable verbose logging
```

### SEE ALSO

* [tilt alpha](tilt_alpha.html)	 - unstable/advanced commands still in alpha

###### Auto generated by spf13/cobra on 19-Feb-2021