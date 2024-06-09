# The project is a proprietary implementation of the STL library.

The code is written according to google style.
The library implements structures such as:
- List
- Map
- Set
- Queue
- Stack
- Vector
- Array
- Multiset

# Project Instructions

## Overview

This project includes a set of tests for a C++ project, and it uses various tools such as Google Test, Valgrind, and gcov for testing, memory leak checking, and code coverage. The provided `Makefile` automates the building, testing, and cleaning processes.

## Prerequisites

Ensure you have the following tools installed:

- `g++` (GNU Compiler Collection)
- `make`
- `Google Test` (`gtest`)
- `lcov` (for generating coverage reports)
- `clang-format` (for code formatting)
- `valgrind` (for memory leak checking on Linux)
- `leaks` (for memory leak checking on macOS)

## Makefile Targets

The `Makefile` includes several targets to automate the workflow:

### 1. `all`
This is the default target that cleans the project and runs the tests.
```sh
make all
```

### 2. `test`
Compiles and runs all the tests.
```sh
make test
```

### 3. `gcov_report`
Generates a code coverage report.
```sh
make gcov_report
```

### 4. `style`
Checks the code formatting according to the Google style.
```sh
make style
```

### 5. `leaks`
Runs the tests and checks for memory leaks.
```sh
make leaks
```

### 6. `clean`
Cleans up all generated files.
```sh
make clean
```

*** 

This project was developed by a students of School 21: jereyji, shaunna, gehnbrig, luanarau
