# C++ Repository Validator

Automated validation framework for C++ open-source repositories.
Runs builds, executes tests, and generates coverage reports in isolated Docker environments.

## Features

- **Build Verification**: CMake + Make configuration testing
- **Test Execution**: Automated unit test runs with failure detection
- **Coverage Analysis**: gcov-based code coverage reporting
- **Docker Isolation**: Reproducible environments across repositories

## Usage

```bash
./validate.sh  
```

## Example

Validates a repository against multiple C++ standards and compiler configurations.

## Technologies

C++ | CMake | Docker | Bash
