# Mylib_c

Biblioteca própria em C desenvolvida como parte da formação da 42 Rio.

O projeto recria funções importantes da biblioteca padrão do C e adiciona funções auxiliares que podem ser reutilizadas em outros projetos da formação. A proposta é entender melhor manipulação de memória, strings, listas encadeadas e organização de código modular.

## Objetivo

Construir uma biblioteca estática (`libft.a`) com funções implementadas do zero, reforçando fundamentos de C e servindo como base para projetos posteriores.

## Tecnologias e conceitos utilizados

- C
- Makefile
- Biblioteca estática (`.a`)
- Ponteiros e alocação dinâmica
- Manipulação de memória
- Manipulação de strings
- Listas encadeadas
- Organização modular
- Normas de codificação da 42

## Funcionalidades implementadas

O `Makefile` compila funções como:

- manipulação de memória: `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_memcmp`, `ft_memchr`, `ft_bzero`;
- manipulação de strings: `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strdup`, `ft_strjoin`, `ft_substr`, `ft_split`, `ft_strtrim`, `ft_strnstr`;
- conversões e validações: `ft_atoi`, `ft_itoa`, `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`;
- escrita em file descriptors: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`;
- funções bônus para listas encadeadas.

## Como compilar

```sh
git clone https://github.com/vinionix/Mylib_c.git
cd Mylib_c
make
```

O comando gera o arquivo:

```text
libft.a
```

Para compilar também as funções bônus:

```sh
make bonus
```

Para limpar os arquivos gerados:

```sh
make clean
make fclean
make re
```

## Como usar em outro projeto

Exemplo de compilação usando a biblioteca gerada:

```sh
cc main.c -L. -lft -I.
```

## Status atual

Projeto base implementado com as funções principais e bônus previstas no `Makefile`.

O repositório não informa testes automatizados ou resultado de avaliação. A documentação foi escrita com base nos arquivos presentes no projeto.

## Evolução do projeto

- Implementação das funções principais da libc.
- Inclusão de funções auxiliares para manipulação de strings, memória e conversões.
- Implementação das funções bônus de lista encadeada.
- Geração da biblioteca estática `libft.a` via `make`.
- Fase atual: projeto consolidado como base reutilizável para outros projetos em C.

## Aprendizados principais

- Funcionamento interno de funções comuns da libc.
- Uso de ponteiros, buffers e alocação dinâmica.
- Criação de biblioteca estática em C.
- Estruturação de código reutilizável.
- Manipulação de listas encadeadas.
- Disciplina com Makefile e padrões de projeto da 42.

## Autor

Desenvolvido por [vinionix](https://github.com/vinionix) durante a formação na 42 Rio.
