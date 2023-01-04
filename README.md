# hellocppwithgoogletest

## Build

* Generating CMake's build files

```sh
cmake -S . -B build
```

* Compile

```sh
cmake --build build
```

* Testing

```sh
ctest --test-dir build
```

Example

```sh
ctest --test-dir build
Internal ctest changing into directory: /home/arch/workspace/hellocpp/build
Test project /home/arch/workspace/hellocpp/build
    Start 1: HelloTest.BasicAssertions
1/1 Test #1: HelloTest.BasicAssertions ........   Passed    0.00 sec

100% tests passed, 0 tests failed out of 1

Total Test time (real) =   0.00 sec
```
