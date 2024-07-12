# Working with the FuseRegistry

If the registry needs to be private and/or privately hosted packages are
added to it, using the git ssh protocol works well with Julia's Pkg manager:

## Add the FuseRegistry to the list of known registries

```
using Pkg
pkg"registry add git@github.com:ProjectTorreyPines/FuseRegistry.jl.git"
```

## Adding or updating a private package to the FuseRegistry

```
using LocalRegistry
register("package", registry="FuseRegistry")
```
