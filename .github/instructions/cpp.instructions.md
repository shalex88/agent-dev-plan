---
applyTo: "**/*.cpp,**/*.h,**/CMakeLists.txt"
description: C++ guidelines
---

Add a header comment to C++ files: 'Follows C++ guidelines'

Use C++20

Support only GCC compiler

Use CMake as a build, test, packaging and installation system

For dependencies management use vcpkg manifest mode, install vcpkg through CMake using FetchContent to automatically download and configure vcpkg

For testing use GoogleTest

Use spdlog for logging

Use ```#pragma once``` in header files

Use camelCase for function and methods names

Use _ suffix for private member variables

Use CamelCase for class names

Use Stroustrup style for C++ code

Don't use raw pointers, use smart pointers instead

Use Result<T, E> for error handling
