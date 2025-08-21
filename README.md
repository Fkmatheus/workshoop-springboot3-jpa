# 📚 Workshop Spring Boot 3 + JPA

Projeto de uma E-commerce API RESTful desenvolvida com Spring Boot 3 e JPA. A aplicação simula operações de CRUD utilizando um banco de dados H2 em memória.  

---

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot 3.5.4
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

---

## 📁 Estrutura do Projeto

src/main/java/com/educandoweb/course/  
├── entities/  Entidades JPA (User, Order, Product etc.)  
├── repositories/  Interfaces JPA  
├── resources/  Controladores REST  
├── services/  Regras de negócio  
└── exceptions/  Tratamento de erros personalizados  

---

## 📂 Banco de Dados
 - Utiliza o H2 Database em memória

---  

## 🔄 Endpoints REST (Exemplo)
Os endpoints podem variar de acordo com as entidades implementadas. Aqui estão exemplos típicos:

👤 Usuários (/users)
 - GET /users → Lista todos os usuários

 - GET /users/{id} → Retorna um usuário por ID

 - POST /users → Cria um novo usuário

 - PUT /users/{id} → Atualiza um usuário existente

 - DELETE /users/{id} → Deleta um usuário  


📦 Produtos (/products)
 - GET /products

 - POST /products

 - (etc.)

---

# 📌 Objetivos do Projeto  

- Praticar conceitos modernos com Spring Boot 3  
- Implementar uma arquitetura em camadas (Controller, Service, Repository)  
- Utilizar JPA/Hibernate com banco em memória (H2)  
- Criar uma API RESTful completa com operações CRUD  
- Aplicar boas práticas de estruturação e tratamento de exceções  



  
