# 📚 Library Management System (C)

<p align="center">
  <strong>Console-based library management system written in C</strong>
</p>

<p align="center">
  Manages books, users, and loans with file persistence, automatic due-date tracking, reports, and advanced search.
</p>

<p align="center">
  <a href="#-english">English</a> · <a href="#-português">Português</a>
</p>

---

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-brightgreen?style=for-the-badge)

---

## 🇧🇷 Português

### 📖 Sobre

Sistema em **C** para controle de biblioteca: cadastro de livros e usuários, controle de empréstimos e devoluções, cálculo automático de prazos, relatórios e persistência de dados em arquivo.

Desenvolvido inicialmente como atividade acadêmica e depois expandido e refinado como projeto pessoal de portfólio.

### ✨ Funcionalidades

- 📗 Cadastro de livros e usuários
- 🔄 Controle de empréstimos e devoluções
- 📅 Cálculo automático de prazo de entrega (`time.h`)
- ⏰ Verificação de atrasos
- 💾 Persistência em arquivos `.txt`
- 🗂️ Sistema de backup automático

### 📊 Relatórios

- Empréstimos ativos
- Empréstimos em atraso
- Livros mais emprestados
- Busca avançada de livros por múltiplos critérios

### 🛠️ Tecnologias

- Linguagem C
- Manipulação de arquivos
- Estruturas de dados (structs, listas)
- Biblioteca `time.h` para controle de datas
- Programação estruturada

### 📂 Estrutura do Projeto

```
C-librarySystem/
│
├── include/     # Headers (.h) — structs e assinaturas das funções
├── src/         # Implementação (.c) — lógica de livros, usuários, empréstimos e relatórios
└── .gitignore
```

### 🚀 Como executar

**Requisitos:** GCC (ou outro compilador C) e Git.

```bash
# 1. Clone o repositório
git clone https://github.com/Vinicius-luciano/C-librarySystem.git
cd C-librarySystem

# 2. Compile
gcc -Iinclude src/*.c -o library

# 3. Execute
./library        # Linux/macOS
library.exe      # Windows
```

> Os dados de livros, usuários e empréstimos são salvos automaticamente em arquivos `.txt` na pasta do projeto.

---

## 🇬🇧 English

### 📖 About

Library Management System written in **C**: book and user registration, loan/return control, automatic due-date calculation, reports, and file-based data persistence.

Initially developed as an academic project and later expanded and refined as a personal portfolio project.

### ✨ Features

- 📗 Book and user registration
- 🔄 Loan and return management
- 📅 Automatic due-date calculation (`time.h`)
- ⏰ Late return verification
- 💾 Data persistence in `.txt` files
- 🗂️ Automatic backup system

### 📊 Reports

- Active loans
- Overdue loans
- Most borrowed books
- Advanced book search by multiple criteria

### 🛠️ Technologies

- C programming language
- File handling
- Data structures (structs, lists)
- `time.h` library for date control
- Structured programming

### 📂 Project Structure

```
C-librarySystem/
│
├── include/     # Headers (.h) — structs and function signatures
├── src/         # Implementation (.c) — book, user, loan, and report logic
└── .gitignore
```

### 🚀 Getting Started

**Requirements:** GCC (or another C compiler) and Git.

```bash
# 1. Clone the repository
git clone https://github.com/Vinicius-luciano/C-librarySystem.git
cd C-librarySystem

# 2. Compile
gcc -Iinclude src/*.c -o library

# 3. Run
./library        # Linux/macOS
library.exe      # Windows
```

> Book, user, and loan data is automatically saved to `.txt` files in the project folder.

---

## 👨‍💻 Author

**Vinícius Luciano**

Software Engineering student interested in software development, Artificial Intelligence, and automation.

[GitHub](https://github.com/Vinicius-luciano)
