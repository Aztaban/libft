# Libft – Enhanced Standard C Library

This project is a personal, enhanced version of the 42 school's `libft`. It reimplements key standard C library functions while introducing new utilities and features designed to support a wide range of C projects — from basic parsing to more complex memory and list manipulations.

The goal is to provide a solid foundation that can be reused across multiple 42 and personal projects, with ongoing improvements and additions.

---

## ✨ Highlights

- Full reimplementation of standard libc functions using only allowed functions
- Bonus utility functions for memory, strings, and character processing
- Linked list manipulation support (`t_list` and related helpers)
- Modular, norm-compliant, and easy to maintain
- Ready to plug into 42 projects
- Continuously updated with new utilities and helper functions

---

## 🛠️ Build Instructions

To compile the library:

```bash
make
```
This will generate the libft.a static library file.

## 📚 How to Use

1. Include the main header in your C file:

```c
#include "libft.h"
```

2. Link the library during compilation:

```bash
gcc your_code.c -L. -lft
```
3. Use any of available functions


## ✅ Makefile Targets
make – compiles the library

make clean – removes object files

make fclean – removes object files and the compiled library

make re – cleans and rebuilds the library

## 👤 Author

Created and maintained by [Martin Justa](https://github.com/aztaban) as part of the 42 school curriculum.