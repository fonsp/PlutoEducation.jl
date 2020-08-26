# julia-pkg-template

This is a basic template repository for generating [Julia][julia] package.
See the documentation for Julia's package manager [Pkg][pkg] for more details.

## How to use this template?

When you have created a repository based on this template you should search and replace the
following placeholders

| Placeholder      | New value                                                |
|------------------|----------------------------------------------------------|
| PACKAGE_NAME     | The name of your Julia package                           |
| PACKAGE_UUID     | A newly generated UUID, e.g. from `using UUIDs; uuid4()` |
| PACKAGE_AUTHOR   | Your full name.                                          |
| GITHUB_USER      | Your GitHub username (or the name of the organization)   |

You also need to rename the file `src/PACKAGE_NAME.jl` accordingly.
Finally, you can replace this file (`README.md`) with `README.template.md`.

[julia]: https://julialang.org/
[pkg]: https://julialang.github.io/Pkg.jl/v1/
