## havener watch

Watch status of all pods in all namespaces

### Synopsis

Continuesly creates a list of all pods in all namespaces.

```
havener watch [flags]
```

### Options

```
  -c, --crd string          crd to watch, based on the singular or short-name of the resource
  -h, --help                help for watch
  -i, --interval int        interval between measurements in seconds (default 2)
  -n, --namespace strings   comma separated list of namespaces to filter (default is to use all namespaces
  -r, --resource string     resource to watch (default to pods)
```

### Options inherited from parent commands

```
      --debug                 debug output - level 5
      --error                 error output - level 2
      --fatal                 fatal output - level 1
      --kubeconfig string     Kubernetes configuration (default "~/.kube/config")
      --terminal-height int   disable autodetection and specify an explicit terminal height (default -1)
      --terminal-width int    disable autodetection and specify an explicit terminal width (default -1)
      --trace                 trace output - level 6
  -v, --verbose               verbose output - level 4
      --warn                  warn output - level 3
```

### SEE ALSO

* [havener](havener.md)	 - Convenience wrapper around some kubectl commands

