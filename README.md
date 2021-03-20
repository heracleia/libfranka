# libfranka: C++ library for Franka Emika research robots

[![Build Status][travis-status]][travis]
[![codecov][codecov-status]][codecov]

With this library, you can control research versions of Franka Emika robots. See the [Franka Control Interface (FCI) documentation][fci-docs] for more information about what `libfranka` can do and how to set it up. The [generated API documentation][api-docs] also gives an overview of its capabilities.

## License

`libfranka` is licensed under the [Apache 2.0 license][apache-2.0].

[apache-2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[api-docs]: https://frankaemika.github.io/libfranka
[fci-docs]: https://frankaemika.github.io/docs
[travis-status]: https://travis-ci.org/frankaemika/libfranka.svg?branch=master
[travis]: https://travis-ci.org/frankaemika/libfranka
[codecov-status]: https://codecov.io/gh/frankaemika/libfranka/branch/master/graph/badge.svg
[codecov]: https://codecov.io/gh/frankaemika/libfranka

## 0.7.0 libfranka version non RT Patch
This is a patched version of libfranka which runs in liquorix kernel. To use this download this source of libfranka in your catkin workspace and build it and subsequently re-build your catkin workspace. That should do the trick for running libfranka in Non-RT kernels! Please read this Github repo README: https://github.com/heracleia/Libfranka-Non-RT-Patch before using this source just as an FYI. Thanks!
