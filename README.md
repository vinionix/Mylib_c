# 📚 Mylib_c

O **Mylib_c** é o primeiro projeto da 42. O objetivo é recriar funções da biblioteca padrão do C e desenvolver uma biblioteca própria que será reutilizada em diversos projetos ao longo da formação.  

Este projeto permite entender a fundo o funcionamento da **libc**, ganhar experiência com manipulação de memória e aprender a estruturar código modular e reutilizável.

---

## ✨ Funcionalidades
- Reimplementação de funções da **libc**:  
  - Manipulação de memória (`memset`, `memcpy`, `memmove`, etc.)  
  - Manipulação de strings (`strlen`, `strdup`, `strjoin`, etc.)  
  - Conversão de caracteres e números (`atoi`, `toupper`, `tolower`, etc.)  
- Funções adicionais:  
  - Manipulação de listas encadeadas (`t_list`, `ft_lstnew`, `ft_lstadd_back`, etc.)  
  - Funções auxiliares criadas do zero para facilitar desenvolvimento em outros projetos  

---

## 🛠️ Tecnologias e Conceitos
- **Linguagem C**  
- Manipulação de memória e ponteiros  
- Estruturas de dados (listas encadeadas)  
- Organização modular de código  
- Normas de codificação da 42  
- Compilação de bibliotecas estáticas (`.a`)  

---

## 🚀 Como executar
1. Clone o repositório:  
bash
git clone https://github.com/vinionix/Mylib_c.git
cd libft
Compile a biblioteca:

bash
Copiar código
make
O arquivo libft.a será gerado e pode ser usado em outros projetos:

bash
Copiar código
gcc main.c -L. -lft -I./includes

---

## 📚 Aprendizados principais
- Entendimento profundo da **libc** e funções de C.
- Manipulação de memória e ponteiros.
- Criação e gerenciamento de listas encadeadas.
- Estruturação de código modular e reutilizável.
- Disciplina para seguir normas de codificação da 42.

---

## 📌 Roadmap (futuras implementações)
- [ ] Testes automatizados completos.
- [ ] Documentação detalhada de cada função.
- [ ] Exemplos de uso em pequenos projetos.
- [ ] Versão estendida com funções extras avançadas.

---

## 👤 Autor
- **[Vinicius Fidelis]**
