## sealos build

build an cloud image from a Kubefile

```
sealos build [flags] PATH
```

### Examples

```
sealos build -t labring/kubernetes:v1.24.0 .
```

### Options

```
  -h, --help                 help for build
  -f, --kubefile string      kubefile filepath (default "Kubefile")
  -m, --max-pull-procs int   maximum number of goroutines for pulling (default 5)
      --platform string      set the OS/ARCH/VARIANT of the image to the provided value instead of the current operating system and architecture of the host (for example linux/arm) (default "linux/amd64")
  -t, --tag string           tagged name to apply to the built image
```

### Options inherited from parent commands

```
      --cluster-root string   cluster root directory (default "/var/lib/sealos")
      --debug                 enable debug logger
```

### SEE ALSO

* [sealos](sealos.md)	 - simplest way install kubernetes tools.

###### Auto generated by spf13/cobra on 13-Oct-2022