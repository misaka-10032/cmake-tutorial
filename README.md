# Cmake tutorial

Follows the [official tutorial](https://cmake.org/cmake-tutorial/).

### Debug

In command line,

```
cmake -LAH
```

or in `CMakeLists.txt`,

```
message(...)
``` 

### Brief

* Step 1: A basic starting point
 * `cmake_minimum_required`
 * `project`
 * `add_executable`
 * `include_directories`
 * `set`
 * `configure_file`
 * `#define XX @XX@` in configure file
 * `message`
* Step 2: Adding a library
 * `add_library`
 * `include_directories`
 * `add_subdirectory`
 * `target_link_libraries`
 * `option`
* Step 3: Installing and testing
 * `install`
 * `include(CTest)`, `addtest(...)`, `set_tests_properties(...)`
 * `macro`
* Step 4: Adding system introspection
 * `check_function_exists`
 * `#cmakedefine XXX`
 * `add_custom_command`
* Step 5: Adding a generated file and generator
