## havener logs

Retrieve log files from all pods

### Synopsis

Loops over all pods and all namespaces to download log and configuration
files from some well-known hard-coded locations to a local directory. Use this
to quickly scan through multiple files from multiple locations in case you have
to debug an issue where it is not clear yet where to look.

The download includes all deployment YAMLs of the pods and the describe output.

```
havener logs [flags]
```

### Options

```
  -h, --help              help for logs
      --no-config-files   exclude configuration files in download package
      --parallel int      number of parallel download jobs (default 64)
      --target string     desired target download location for retrieved files (default "/tmp")
      --timeout int       allowed time in seconds before the download is aborted (default 300)
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

