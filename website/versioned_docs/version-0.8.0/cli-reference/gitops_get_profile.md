## gitops get profile

Show information about available profiles

```
gitops get profile [flags]
```

### Examples

```

# Get all profiles
gitops get profiles

```

### Options

```
  -h, --help          help for profile
      --port string   Port the profiles API is running on (default "9001")
```

### Options inherited from parent commands

```
  -e, --endpoint string            The Weave GitOps Enterprise HTTP API endpoint
      --insecure-skip-tls-verify   If true, the server's certificate will not be checked for validity. This will make your HTTPS connections insecure
      --namespace string           The namespace scope for this operation (default "flux-system")
  -v, --verbose                    Enable verbose output
```

### SEE ALSO

* [gitops get](gitops_get.md)	 - Display one or many Weave GitOps resources

###### Auto generated by spf13/cobra on 29-Apr-2022