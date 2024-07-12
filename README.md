# Working with the FuseRegistry

### Add the FuseRegistry to the list of known registries

```
using Pkg
pkg"registry add git@github.com:ProjectTorreyPines/FuseRegistry.jl.git"
```

### Adding or updating a private package to the FuseRegistry

```
using LocalRegistry
register("package", registry="FuseRegistry")
```
