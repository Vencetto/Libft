# Libft
Libft - library with basic tools: work with numbers, strings, casts etc. A lot of these functions are copies of standart C library functions.

# It contains:
(non descripted functions are copies of standart C library functions or have description in their names)

## 1. Strings (arrays of chars):
* ft_chars - returns number of chars in string.
* ft_strcat
* ft_strchr
* ft_strclr
* ft_strcmp
* ft_strcpy
* ft_strdel
* ft_strdup - str duplicate.
* ft_strequ
* ft_striter
* ft_striteri
* ft_strjoin
* ft_strlcat
* ft_strlen
* ft_strmap
* ft_strmapi
* ft_strncat
* ft_strncmp
* ft_strncpy
* ft_strnequ
* ft_strnew
* ft_strnstr
* ft_strrchr
* ft_strsplit
* ft_strstr
* ft_strsub
* ft_strtrim

## 2. Memory:
* ft_bzero
* ft_memalloc - malloc + bzero;
* ft_memccpy
* ft_memchr - searches for a char in memory.
* ft_memcmp
* ft_memcpy
* ft_memdel - takes as a parameter the address of a memory area that needs to be freed with free.
* ft_memmove
* ft_memset

## 3. Cast:
* ft_atoi
* ft_itoa 

## 4. Lists:
* ft_lstadd - adds new element to the start(head) of the list.
* ft_lstdel - iterates through list and apply del function on each element.
* ft_lstdelone - delete one element in list.
* ft_lstend - adds new element to the end of the list.
* ft_lstiter - iterates through list and apply given function on each element.
* ft_lstmap - iterates a list and applies given function to each link to create a “fresh” list.
* ft_lstnew - allocates and returns a “fresh” link.

## 5. Output:
* ft_putchar
* ft_putchar_fd - ft_putchr + file descriptor.
* ft_putendl
* ft_putendl_fd
* ft_putnbr
* ft_putnbr_fd
* ft_putstr
* ft_putstr_fd

## 6. Numbers:
* ft_isalnum
* ft_isalpha
* ft_isascii
* ft_isdigit
* ft_isprint

## 7. Additional functions:
* ft_abs
* ft_tolower
* ft_toupper

