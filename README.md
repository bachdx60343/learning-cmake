# learning-cmake

This is a simple CMake tutorial project which contains some different scenarios.

* `hello-world`: Demo a simplest CMake project.
* `hello-world-clear`: Separate the output files and src files.
* `hello-world-lib`: Demo how to make a static/shared library.
* `hello-world-shared`: Demo how to utilize external static/shared library.
* `curl`: Demo how to use cmake with curl.
* `hello-module`: Demo how to use cmake find module.
* `config-file`: Demo how to work with config.h.

## Build steps
* `cmake -H. -B_builds`
* `cmake --build _builds`

## CMake based tools
* [hunter](https://github.com/ruslo/hunter): CMake-driven cross-platform package manager for C++.
* [CLion](https://www.jetbrains.com/clion/): CMake based IDE.

## Nice CMake tutorials
* [CMake Practice](docs/cmake-practice.pdf)
* [CMake rules](docs/cmake-rules.pdf)
* [Mastering CMake](docs/mastering-cmake.pdf)
* [CGold: The Hitchhiker’s Guide to the CMake](https://cgold.readthedocs.io/en/latest/index.html)
