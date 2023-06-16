## sealos pull

pull cloud image

```
sealos pull [flags]
```

### Examples

```
sealos pull labring/kubernetes:v1.24.0
```

### Options

```
  -h, --help              help for pull
      --platform string   set the OS/ARCH/VARIANT of the image to the provided value instead of the current operating system and architecture of the host (for example linux/arm) (default "linux/amd64")
```

### Options inherited from parent commands

```
      --cluster-root string   cluster root directory (default "/var/lib/sealos")
      --debug                 enable debug logger
```

### SEE ALSO

* [sealos](sealos.md)	 - simplest way install kubernetes tools.

###### Auto generated by spf13/cobra on 13-Oct-2022