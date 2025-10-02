# Libft

O **Libft** é o primeiro projeto da 42. O objetivo é recriar funções da biblioteca padrão do C e desenvolver uma biblioteca própria que será reutilizada em diversos projetos ao longo da formação.

---

## 🚀 Funcionalidades

- Implementação de funções da **libc**:  
  - Manipulação de memória (`memset`, `memcpy`, `memmove`, etc.)  
  - Manipulação de strings (`strlen`, `strdup`, `strjoin`, etc.)  
  - Conversão de caracteres e números (`atoi`, `toupper`, `tolower`, etc.)  

- Funções extras para facilitar o desenvolvimento:  
  - Manipulação de listas encadeadas (`t_list`, `ft_lstnew`, `ft_lstadd_back`, etc.)  
  - Funções auxiliares criadas do zero.  

---

## 📂 Estrutura

```bash
Libft/
├── libft.h        # Header com protótipos
├── *.c            # Implementação das funções
├── Makefile       # Automação da compilação
└── README.md      # Documentação
⚙️ Compilação
Clone o repositório e use o Makefile:

bash
Copiar código
git clone https://github.com/seu-usuario/libft.git
cd libft
make
Isso gera o arquivo libft.a, que pode ser usado em outros projetos:

bash
Copiar código
gcc main.c -L. -lft -I.
✅ Testes
Testadores recomendados:

libft-unit-test

libftTester

🎯 Objetivo do Projeto
Entender a fundo como funciona a libc

Ganhar experiência com manipulação de memória

Aprender a estruturar bibliotecas reutilizáveis

Ter disciplina com as normas da 42
