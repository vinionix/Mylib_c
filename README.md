Libft

A Libft é a primeira biblioteca desenvolvida como projeto da 42. O objetivo é recriar um conjunto de funções básicas da linguagem C, além de implementar funções adicionais, que servirão de base para futuros projetos.

📚 Objetivo do Projeto

Reimplementar funções da biblioteca padrão C (<string.h>, <stdlib.h>, etc.).

Criar novas funções utilitárias para manipulação de strings, memória e listas encadeadas.

Servir como fundação para todos os próximos projetos da 42.

🛠️ Funcionalidades
Funções da libc

ft_strlen, ft_strncmp, ft_strdup, ft_strchr, ft_strrchr, ft_strnstr

ft_memset, ft_memcpy, ft_memmove, ft_memcmp, ft_memchr

ft_atoi, ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint, ft_toupper, ft_tolower

ft_calloc

Funções adicionais

Manipulação de strings (ft_substr, ft_strjoin, ft_strtrim, ft_split, ft_strmapi, ft_striteri)

Manipulação de números (ft_itoa)

Manipulação de memória e saída (ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd)

Bonus – Listas encadeadas (t_list)

ft_lstnew, ft_lstadd_front, ft_lstsize, ft_lstlast, ft_lstadd_back

ft_lstdelone, ft_lstclear, ft_lstiter, ft_lstmap

⚙️ Como compilar

Clone o repositório e use o comando:

make


Isso irá gerar o arquivo libft.a, que pode ser utilizado para compilar outros programas em C:

gcc -Wall -Wextra -Werror main.c libft.a -o program

✅ Normas

Todas as funções seguem a Norminette (norma de código da 42).

Máximo de 25 linhas por função (sem contar chaves).

Arquivos organizados por tipo de função.

📂 Estrutura do Projeto
libft/
├── Makefile
├── libft.h
├── ft_*.c

🧑‍💻 Autor

Projeto desenvolvido por Vinionix
 como parte do currículo da 42 Rio
.
