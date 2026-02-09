# Sistema de Login em PHP

Sistema de autenticação desenvolvido em PHP com MySQL, focado em segurança,
organização de código e visual profissional.

Projeto criado para fins de portfólio, demonstrando conhecimentos práticos
em back-end, controle de sessões e integração com banco de dados.

---

## 🚀 Funcionalidades

- Cadastro de usuários
- Login com autenticação segura
- Senhas criptografadas com password_hash
- Validação de email duplicado
- Controle de sessão
- Logout
- Proteção de páginas restritas
- Interface premium (preto e dourado)

---

## 🛠️ Tecnologias Utilizadas

- PHP
- MySQL
- HTML5
- CSS3
- Sessões PHP
- Git & GitHub

---

## 🗄️ Banco de Dados

```sql
CREATE DATABASE sistema_login;
USE sistema_login;

CREATE TABLE usuarios (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nome VARCHAR(100),
  email VARCHAR(100) UNIQUE,
  senha VARCHAR(255)
);
