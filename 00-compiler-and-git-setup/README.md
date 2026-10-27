# Assignment 0: Compiler and Git Setup

Compile a C program with GCC, run the executable, and submit the source through Git.

## How It Works

The exercise introduces the Unix working directory, compiler invocation, executable files, and the connection between a local source file and a Git repository.

## Main Tasks

- Create an assignment directory and a small source file.
- Compile and run the program from a terminal.
- Commit the source and submit its repository link.

## Files

- [test.c](test.c): C demonstration program.
- [test.cpp](test.cpp): C++ demonstration program.
- [Assignment0_S25.pdf](Assignment0_S25.pdf): assignment instructions or submitted report in PDF format.

The included `test.c` prints the numeric values of two characters, while `test.cpp` prints a greeting.

## Compile the Included Examples

From this assignment folder, use GCC for the C example and a C++ compiler for the C++ example:

```bash
gcc test.c -o test-c
./test-c
g++ test.cpp -o test-cpp
./test-cpp
```

The first example prints character codes; the second prints a greeting.
