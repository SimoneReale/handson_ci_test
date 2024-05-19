# CI/CD and Unit Testing Exercise Session

## Getting Started
Git, the simple guide: https://rogerdudler.github.io/git-guide/
Google Test Primer: https://google.github.io/googletest/primer.html
A selected list of useful actions: https://github.com/sdras/awesome-actions

### Prerequisites
Ensure you have the following installed:
- C++ compiler (e.g., g++, clang++)
- CMake
- Git
- Human Brain

### Setup Instructions

1. **Use the template:**
```sh
https://github.com/SimoneReale/handson_ci_test
cd your-repo-name
```
   
3. **Build the project:**
```sh
mkdir build
cd build
cmake ..
cmake --build .
```
3. **Test:**
In the build folder:
```sh
ctest
```
or:
```sh
./tests
```




