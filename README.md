# FlexJuMP.jl

A JuMP extension for analyzing and quantifying the flexibility of complex systems.
Please note that support for FlexJuMP is discontinued in favor of [FlexibilityAnalysis.jl](https://github.com/pulsipher/FlexibilityAnalysis.jl) which is the supported registered package that replaces FlexJuMP.

| **Documentation**                                                               | **Build Status**                                                                                |
|:-------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------:|
| [![](https://img.shields.io/badge/docs-latest-blue.svg)](https://pulsipher.github.io/FlexJuMP.jl/dev) | [![Build Status](https://travis-ci.org/pulsipher/FlexJuMP.jl.svg?branch=master)](https://travis-ci.org/pulsipher/FlexJuMP.jl) [![Build Status2](https://ci.appveyor.com/api/projects/status/github/pulsipher/FlexJuMP.jl?branch=master&svg=true)](https://ci.appveyor.com/project/pulsipher/FlexJuMP-jl) [![codecov.io](http://codecov.io/github/pulsipher/FlexJuMP.jl/coverage.svg?branch=master)](http://codecov.io/github/pulsipher/FlexJuMP.jl?branch=master) |

Comments, suggestions and improvements are welcome and appreciated.

## License
`FlexJuMP` is licensed under the [MIT "Expat" license](./LICENSE.md).

## Installation
FlexJuMP.jl is not yet a registered Julia package, but can still be installed by providing the package manager
with the url of the repository instead of the name.

```julia
using Pkg
Pkg.add("git://github.com/pulsipher/FlexJuMP.jl.git")
```

## Documentation
[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://pulsipher.github.io/FlexJuMP.jl/dev)

Please visit our [documentation pages](https://pulsipher.github.io/FlexJuMP.jl/dev) to learn all you need to know to get started and more. We provide
a quick start guide, an overview necessary background material, a detailed user guide, examples, and
an API library.

## Project Status

The package is tested against Julia `0.7`, `1.0`, and `1.1` on Linux, macOS, and Windows.

A working version for Julia `0.6` can be found in the julia-0.6 branch.

## Contributing
FlexJuMP is being actively developed and suggestions or other forms of contribution are encouraged.
There are many ways to contribute to this package:

- Suggest new/improved functionality
- Report an issue if you encounter some odd behavior, or if you have suggestions to improve the package.
- Contribute with code addressing some open issues, that add new functionality or that improve the performance.
- When contributing with code, add docstrings and comments, so others may understand the methods implemented.
- Contribute by updating and improving the documentation.
