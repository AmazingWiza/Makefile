# Makefile
## make terminal commands

### make
* builds bin/main executable
* builds tests/bin/*.test executables

### make main
* builds bin/main executable

### make run_main
* builds and runs bin/main executable

### make memcheck_main
* runs bin/main executable with Valgrind:  
valgrind --leak-check=yes ./bin/main

### make tests
* builds tests/bin/*.test executables

### make run_tests
* builds and iteratively runs all tests/bin/*.test executables
* Note: VSCode test explorer can be used as an alternative to run tests after they're built

### make run_tests_verbose
* builds and iteratively runs all tests/bin/*.test executables with verbose output
* Note: VSCode test explorer can be used as an alternative to run tests after they're built

### make memcheck_tests
* builds and iteratively runs all tests/bin/*.test executables with Valgrind:   
valgrind --leak-check=yes ./tests/bin/[test_name].test

### make clean
* removes all build artifacts
