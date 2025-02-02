# Sistema de Gestão de Usuários com Testes Unitários

## 📖 Introdução
Este projeto é uma aplicação Java Spring Boot com Testes Unitários

## 💻 Tecnologias Utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/spring%20boot-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Postman](https://img.shields.io/badge/postman-FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white)  ![JUnit](https://img.shields.io/badge/junit-25A162.svg?style=for-the-badge&logo=junit&logoColor=white) ![H2](https://img.shields.io/badge/H2-4E6F1F.svg?style=for-the-badge&logo=h2&logoColor=white)


## Funcionalidades
- **CRUD de Usuários:** Adicionar, visualizar, atualizar e remover usuários.
- **Testes Unitários:** Garantir que as funcionalidades de CRUD e busca funcionem corretamente com testes automatizados.

## Como Configurar e Executar

#### 1. **Configurar o Ambiente:**
   - Instale o [Spring Tool Suite (STS)](https://spring.io/tools).
   - Clone o repositório do projeto em sua máquina local.

#### 3. **Executar o Projeto:**
   - Abra o projeto no STS.
   - Execute a classe principal do Spring Boot (`Application.java`).
   - Use o Postman para interagir com as APIs.
   - H2 é usado como banco em memória



## 🛠️ API Endpoints

### **Usuários:**
- `GET /users` - Lista todos os usuários.
- `POST /users` - Cria um novo usuário.
- `PUT /users/{id}` - Atualiza um usuário existente.
- `DELETE /users/{id}` - Remove um usuário.

## 🧪 Testes Unitários
Os testes unitários foram implementados para garantir que os serviços de usuários funcionem corretamente. Utilizamos o **JUnit 5** e **Mockito** para simular o comportamento das dependências.


