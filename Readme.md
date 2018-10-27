# irpy

This is a copy of the LLVM IR -> Python compiler from the
hyperkernel ecosystem.
The idea is to make it usable for other OS like verification
projects.

## Build

You can build the `irpy` binary using [meson](mesonbuild.com)
and [ninja](ninja-build.org):

```.sh
mkdir build
cd build
meson .. --buildtype release
ninja
```

## License

The original code from [hv6](https://github.com/locore/hv6/) is
licensed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
All changes on top of that are licensed under BSD 3-Clause "New" or "Revised" License.
