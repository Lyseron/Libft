# Libft

Libft is one of the first projects at 42.
The goal is to recreate a set of standard C library functions, as well as some additional utility functions, in order to build a personal C library that can be reused in future projects.

This project helped me understand memory management, string manipulation, file descriptors, linked lists basics, and how standard C functions work internally.

## Features

### Character checks and conversions

| Function     | Description                                       |
| ------------ | ------------------------------------------------- |
| `ft_isalpha` | Checks if a character is a letter.                |
| `ft_isdigit` | Checks if a character is a digit.                 |
| `ft_isalnum` | Checks if a character is alphanumeric.            |
| `ft_isascii` | Checks if a character belongs to the ASCII table. |
| `ft_isprint` | Checks if a character is printable.               |
| `ft_toupper` | Converts a lowercase letter to uppercase.         |
| `ft_tolower` | Converts an uppercase letter to lowercase.        |

### String functions

| Function      | Description                                                          |
| ------------- | -------------------------------------------------------------------- |
| `ft_strlen`   | Returns the length of a string.                                      |
| `ft_strdup`   | Allocates and returns a duplicate of a string.                       |
| `ft_strchr`   | Locates the first occurrence of a character in a string.             |
| `ft_strrchr`  | Locates the last occurrence of a character in a string.              |
| `ft_strncmp`  | Compares two strings up to a given number of characters.             |
| `ft_strnstr`  | Locates a substring inside a string, limited by a given length.      |
| `ft_strlcpy`  | Copies a string into a buffer with size limitation.                  |
| `ft_strlcat`  | Concatenates strings with size limitation.                           |
| `ft_substr`   | Extracts a substring into a newly allocated string.                  |
| `ft_strjoin`  | Concatenates two strings into a newly allocated string.              |
| `ft_strtrim`  | Removes specified characters from the beginning and end of a string. |
| `ft_split`    | Splits a string into an array of strings using a delimiter.          |
| `ft_strmapi`  | Applies a function to each character and creates a new string.       |
| `ft_striteri` | Applies a function to each character of a string in place.           |

### Memory functions

| Function     | Description                                    |
| ------------ | ---------------------------------------------- |
| `ft_memset`  | Fills a memory area with a specific byte.      |
| `ft_bzero`   | Sets a memory area to zero.                    |
| `ft_memcpy`  | Copies memory from one area to another.        |
| `ft_memmove` | Copies memory safely, even when areas overlap. |
| `ft_memchr`  | Searches for a byte in a memory area.          |
| `ft_memcmp`  | Compares two memory areas.                     |
| `ft_calloc`  | Allocates memory and initializes it to zero.   |

### Conversion functions

| Function  | Description                                      |
| --------- | ------------------------------------------------ |
| `ft_atoi` | Converts a string to an integer.                 |
| `ft_itoa` | Converts an integer to a newly allocated string. |

### File descriptor output

| Function        | Description                                                       |
| --------------- | ----------------------------------------------------------------- |
| `ft_putchar_fd` | Writes a character to a given file descriptor.                    |
| `ft_putstr_fd`  | Writes a string to a given file descriptor.                       |
| `ft_putendl_fd` | Writes a string followed by a newline to a given file descriptor. |
| `ft_putnbr_fd`  | Writes an integer to a given file descriptor.                     |

### Additional utility functions

| Function             | Description                                                         |
| -------------------- | ------------------------------------------------------------------- |
| `ft_contain_char`    | Checks if a string contains a specific character.                   |
| `ft_dba_dup`         | Duplicates a double array of strings.                               |
| `ft_dba_len`         | Returns the number of strings in a double array.                    |
| `ft_extract_path`    | Extracts the part after `=` in an environment variable.             |
| `ft_free_before_i`   | Frees all allocated strings before a given index in a double array. |
| `ft_free_double_tab` | Frees a full double array of strings.                               |

## Compilation

To compile the library:

```bash
make
```

This creates a static library:

```bash
libft.a
```

## Usage

Include the header in your C files:

```c
#include "libft.h"
```

Then compile your project with the library:

```bash
cc main.c libft.a
```

## Skills practiced

* C programming
* Memory allocation
* Pointers
* String manipulation
* File descriptors
* Static libraries
* Makefile
* Reimplementation of standard library functions

