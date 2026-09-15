# 🚀 TaskFlow API

API REST para gerenciamento de tarefas, usuários, produtos, categorias e pedidos, desenvolvida com Java e Spring Boot.

## 🛠️ Tecnologias

- ☕ Java
- 🌱 Spring Boot
- 🗄️ Spring Data JPA
- 🐬 MySQL
- 🐘 PostgreSQL
- 🔧 Maven
- 🔗 Git e GitHub

## 📌 Sobre o projeto

O TaskFlow API foi desenvolvido para praticar conceitos de desenvolvimento Back-End com Java e Spring Boot, incluindo criação de APIs REST, persistência de dados, organização em camadas e aplicação de regras de negócio.

O projeto também foi utilizado para consolidar conhecimentos em JPA, relacionamentos entre entidades e operações de CRUD.

## ⚙️ Funcionalidades

- 👤 Gerenciamento de usuários
- 📦 Gerenciamento de produtos
- 🏷️ Gerenciamento de categorias
- 🛒 Gerenciamento de pedidos
- 🔗 Relacionamentos entre entidades
- 💾 Persistência de dados com JPA/Hibernate
- 🌐 Endpoints REST para acesso aos recursos
- 🧠 Aplicação de regras de negócio

## 🏗️ Organização

O projeto segue uma organização em camadas, buscando separar as responsabilidades da aplicação e facilitar sua manutenção e evolução.

Principais componentes:

- **Controller** — exposição dos endpoints da API
- **Service** — regras e lógica de negócio
- **Repository** — acesso e persistência dos dados
- **Entities** — representação dos dados e relacionamentos

## ▶️ Como executar

### Pré-requisitos

- Java instalado
- Maven instalado
- MySQL ou PostgreSQL configurado

### Clonando o projeto

```bash
git clone https://github.com/fabricio-vianna/taskflow-api.git
```

Entre na pasta:

```bash
cd taskflow-api
```

Execute o projeto:

```bash
./mvnw spring-boot:run
```

No Windows, caso necessário:

```bash
mvnw.cmd spring-boot:run
```

> Configure as credenciais e informações do banco de dados de acordo com o arquivo de configuração do projeto antes de executar.

## 🔮 Possíveis melhorias

Algumas funcionalidades que podem ser adicionadas futuramente:

- 🔐 Autenticação e autorização com Spring Security e JWT
- 📄 Paginação de resultados
- 📚 Documentação da API com Swagger/OpenAPI
- ☁️ Deploy em ambiente de nuvem
- 🧪 Ampliação da cobertura de testes

## 🎯 Objetivo

Projeto desenvolvido com foco no aprendizado e na evolução prática em desenvolvimento Back-End Java, aplicando conceitos estudados em programação orientada a objetos, Spring Boot, persistência de dados e desenvolvimento de APIs REST.

---

💻 Desenvolvido por **Fabricio Vianna**
