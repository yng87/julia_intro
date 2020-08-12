# Julia installation

You need to install Julia (my environment is Julia-1.5.0).

Please follow [the official instruction](https://julialang.org/downloads/).

# Package installation

After installing Julia, enter the REPL by

```
$julia
```

on your terminal.

Then type `]` to enter the package manager.

You can install related libraries by

```
(@v1.5) pkg> activate .
(julia_intro) pkg> instantiate
```
which will download all the libraries written in `Project.toml`.

You may need additional `build` commands to use those libraries.
