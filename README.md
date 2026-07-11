# 🚀 SGP RH API

Sistema de Gestão de Pessoas desenvolvido com **Java 21** e **Spring Boot**, seguindo a arquitetura **MVC** e boas práticas de desenvolvimento de APIs REST.

## 📖 Sobre o Projeto

O objetivo deste projeto é simular uma aplicação utilizada por empresas para gerenciamento de recursos humanos, permitindo o cadastro e administração de funcionários, departamentos e usuários, com autenticação segura e documentação da API.

Este projeto foi desenvolvido para fins de estudo e demonstração de conhecimentos em desenvolvimento Backend com Java.

---

# 🏗️ Arquitetura

O projeto segue a arquitetura MVC (Model-View-Controller), organizada em camadas para facilitar manutenção, escalabilidade e reutilização de código.

```
Cliente (Postman / Front-end)

        │

Controller

        │

Service

        │

Repository

        │

Banco de Dados (MySQL)
```

### Estrutura de Pastas

```
src
└── main
    ├── java
    │   └── br.com.sgp
    │       ├── config
    │       ├── controller
    │       ├── dto
    │       │   ├── request
    │       │   └── response
    │       ├── entity
    │       ├── enums
    │       ├── exception
    │       ├── mapper
    │       ├── repository
    │       ├── security
    │       ├── service
    │       ├── specification
    │       └── util
    └── resources
```

---

# ⚙️ Tecnologias

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Lombok
- Spring Validation
- Swagger / OpenAPI
- Spring Security
- JWT
- Docker
- JUnit 5
- Mockito
- Git
- GitHub

---

# 📦 Funcionalidades

## Funcionários

- Cadastro
- Atualização
- Exclusão
- Consulta por ID
- Consulta por CPF
- Consulta por matrícula
- Paginação
- Filtros

## Departamentos

- Cadastro
- Atualização
- Exclusão
- Listagem

## Usuários

- Cadastro
- Login
- Alteração de senha
- Controle de acesso

---

# 🔐 Segurança

- Spring Security
- JWT Authentication
- BCrypt Password Encoder
- Controle de Perfis (Roles)

Perfis disponíveis:

- ADMIN
- GERENTE
- ANALISTA
- OPERADOR

---

# 📊 Dashboard

O sistema disponibiliza indicadores como:

- Total de funcionários
- Funcionários ativos
- Funcionários inativos
- Média salarial
- Funcionários por departamento

---

# 🗄️ Banco de Dados

Principais tabelas:

- usuarios
- roles
- funcionarios
- departamentos
- cargos
- telefones
- enderecos
- auditoria
- refresh_tokens

---

# 📚 Documentação

Após iniciar a aplicação:

```
http://localhost:8080/swagger-ui/index.html
```

---

# 🧪 Testes

O projeto utiliza:

- JUnit 5
- Mockito
- MockMvc

---

# 🐳 Docker

Para executar com Docker:

```bash
docker-compose up -d
```

---

# 🚀 Executando o Projeto

## Clone

```bash
git clone https://github.com/SEU-USUARIO/sgp-rh-api.git
```

## Entre na pasta

```bash
cd sgp-rh-api
```

## Execute

```bash
./mvnw spring-boot:run
```

ou

```bash
mvn spring-boot:run
```

---

# 📌 Roadmap

- [x] Estrutura MVC
- [x] CRUD Funcionários
- [x] CRUD Departamentos
- [ ] Spring Security
- [ ] JWT
- [ ] Upload de arquivos
- [ ] Exportação PDF
- [ ] Exportação Excel
- [ ] Docker
- [ ] Testes automatizados
- [ ] CI/CD

---

# 👨‍💻 Autor

Thiago Guilherme Monteiro

Desenvolvedor Java | Spring Boot | APIs REST | MySQL

---

## ⭐ Objetivo

Este projeto faz parte da minha jornada de estudos em Java Full Stack e demonstra conhecimentos em arquitetura MVC, desenvolvimento de APIs REST, persistência de dados, autenticação, segurança e boas práticas de desenvolvimento.
