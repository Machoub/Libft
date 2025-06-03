# 📚 Libft – 42 Project

A custom implementation of the C standard library functions.  
Completed as part of the 42 school curriculum.

---

## 📌 Description

Libft is the first project of the 42 cursus.  
It involves recreating standard C functions from `<ctype.h>`, `<string.h>`, and `<stdlib.h>`, along with additional utility functions and linked list operations, to gain a deep understanding of memory and string manipulation in C.

---

## 🛠️ Implemented Functions

### 🔡 Part 1 – Libc Functions
```c
ft_isalpha    ft_isdigit    ft_isalnum    ft_isascii    ft_isprint
ft_strlen     ft_memset     ft_bzero      ft_memcpy     ft_memmove
ft_strlcpy    ft_strlcat    ft_toupper    ft_tolower    ft_strchr
ft_strrchr    ft_strncmp    ft_memchr     ft_memcmp     ft_strnstr
ft_atoi       ft_calloc     ft_strdup
🧪 Part 2 – Additional Functions
c
Copier
Modifier
ft_substr     ft_strjoin    ft_strtrim    ft_split
ft_itoa       ft_strmapi    ft_striteri   ft_putchar_fd
ft_putstr_fd  ft_putendl_fd ft_putnbr_fd
🧵 Bonus – Linked List Utilities
c
Copier
Modifier
ft_lstnew     ft_lstadd_front  ft_lstsize     ft_lstlast
ft_lstadd_back ft_lstdelone    ft_lstclear    ft_lstiter
ft_lstmap
🔧 Build Instructions
To compile the library:

bash
Copier
Modifier
make
To clean up object files:

bash
Copier
Modifier
make clean
To remove everything (object files + lib):

bash
Copier
Modifier
make fclean
To force full rebuild:

bash
Copier
Modifier
make re
This will generate a libft.a file that can be linked to any C project.
