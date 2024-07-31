# FuseRegistry

Registry of Julia packages related to FUSE.jl or more broadly to IMASdd.jl

### Add the FuseRegistry to the list of known registries

```
using Pkg
pkg"registry add git@github.com:ProjectTorreyPines/FuseRegistry.jl.git"
```

### Adding or updating a package to the FuseRegistry

```
using LocalRegistry
register("package", registry="FuseRegistry")
```
