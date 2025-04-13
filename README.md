# Libft V2 (42 School)

An extended version of the standard 42 Libft library. This version includes additional utility functions commonly required for projects within the 42 Common Core curriculum, going beyond the scope of the original `libft` project.

## Purpose

To provide a reusable library of essential C functions, reducing code duplication and effort in subsequent 42 projects.
Also includes `get_next_line` and `ft_printf` functionality.

## Usage

1.  Clone the repository.
2.  Compile the library using the provided `Makefile`:
    ```bash
    make
    ```
    This will create the `libft.a` static library file.
3.  Include the `libft.h` header in your C projects.
4.  Compile your project, linking the library, example:

    ```bash
    cc your_project.o 42_libft_v2/libft/libft.a -o your_executable
    ```
    
