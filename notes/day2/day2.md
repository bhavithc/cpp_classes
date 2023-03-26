- [x] Introduction to C/C++
- [x] Compilation steps in deep
- [x] Versions in C++
- [x] Various commands

**Compilation steps**

1. Preprocessor: Does the copy paste job
2. Proper: Check for the syntax error
3. Assembler: Converts the assembly code into object file
4. Linker: Links the object file with system library `libc`

**Command to generate the intermediate files**
`gcc -save-temps main.c` -> This generates all the intermediate files `main.i`, `main.s` & `main.o`. finally it generates the executable called `a.out`

**Commands to control the compilation**
- `gcc -E main.c` -> It prints the output of console, if needed we need to redirect to the file using `gcc -E main.c > main.i`

- `gcc -S main.c` -> It generates the assembly file
- `gcc -c main.c` -> It generates the object file
- `gcc main.c` -> It generates the binary called `a.out`

*If we want to rename the `a.out` then use `gcc main.c -o main` -> Here main is the name for the executable

**Other commands learnt**
- `ldd`: To see what are the library linked with our executable
- `gcc`: C compiler to compile the source
- `nm`: To print the symbol tables
- `strip`: To remove the symbol tables from the executable
- `gdb`: GNU debugger to debug a.out
   - Compile with `-g` -> `gcc -g main.c`
   - `gdb a.out`
   - `r` -> run 
   - `b` -> breakpoint
   - `c` -> continue
   - `q` -> quit
   - `list` -> To print the source (Provided compiled with `-g` option)

### Version of C++
- Classical C++ (C++98, C++03)
- Modern C++ (C++11, C++14, C++17, C++20, C++23)

### Extra info
- Memory pyramid (Register, L1, L2, L3 caches, RAM, HDD (swap))
- How cross compiler works
- How touch command works for variour target machines
 

