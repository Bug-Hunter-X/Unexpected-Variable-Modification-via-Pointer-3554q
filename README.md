# Unexpected Variable Modification via Pointer in C

This repository demonstrates a simple C program that illustrates a potential issue with pointer manipulation.  The code modifies a variable's value indirectly through a pointer, which is generally correct but may lead to subtle bugs in more complex scenarios (e.g., dangling pointers, memory leaks).

The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

## How to run:

1. Clone this repository.
2. Compile the `bug.c` and `bugSolution.c` files using a C compiler (e.g., GCC):
   ```bash
   gcc bug.c -o bug
   gcc bugSolution.c -o bugSolution
   ```
3. Run the executables:
   ```bash
   ./bug
   ./bugSolution
   ```

Observe the output difference to understand the behavior and how to prevent the error.