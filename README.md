# llvm-releases

The precompiled LLVM binaries does not include the standard library. If you want to use libstdc++, download GCC from the [gcc-release](https://github.com/trcrsired/gcc-releases) and add the `bin`, `lib`, and `lib32` directories to your `PATH`, Clang will then correctly recognize libstdc++. If you prefer to use libc++ or STL, download the [windows-msvc-sysroot](https://github.com/trcrsired/windows-msvc-sysroot) and read the README.md.
