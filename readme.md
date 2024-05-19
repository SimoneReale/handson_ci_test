# CI/CD and Unit Testing Exercise Session

## Getting Started
Git, the simple guide: https://rogerdudler.github.io/git-guide/
Google Test Primer: https://google.github.io/googletest/primer.html

### Prerequisites
Ensure you have the following installed:
- C++ compiler (e.g., g++, clang++)
- CMake
- Git
- Human Brain

### Setup Instructions

1. **Use the template:**
    https://github.com/SimoneReale/handson_ci_test
    cd your-repo-name
   
2. **Build the project:**
	mkdir build
	cd build
	cmake ..
	cmake --build .

## Project Structure
.
├── .github
│   └── workflows
│       └── ci.yml
├── src
│   ├── main.cpp
│   ├── problems.cpp
│   └── problems.h
├── tests
│   └── tests.cpp
├── CMakeLists.txt
└── README.md






