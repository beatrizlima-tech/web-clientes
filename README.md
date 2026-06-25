# 👥 Web Clientes

![Angular](https://img.shields.io/badge/Angular-21-red?style=for-the-badge\&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge\&logo=bootstrap)
![REST API](https://img.shields.io/badge/REST%20API-Integration-blue?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

# 📌 Sobre o projeto

O **Web Clientes** é uma aplicação frontend desenvolvida com **Angular** para gerenciamento de clientes, consumindo uma API REST construída com **Java**, **Spring Boot** e **PostgreSQL**.

A aplicação oferece uma interface moderna para realizar operações de cadastro, consulta, edição e exclusão de clientes, utilizando **Reactive Forms**, **Signals** e **HttpClient**, seguindo boas práticas de desenvolvimento Frontend.

---

# 🚀 Funcionalidades

* Cadastro de clientes
* Consulta de clientes por nome
* Atualização de clientes
* Exclusão de clientes
* Integração completa com API REST
* Formulários reativos
* Gerenciamento de estado com Signals
* Interface responsiva utilizando Bootstrap

---

# 🧱 Tecnologias Utilizadas

* Angular 21
* TypeScript
* HTML5
* CSS3
* Bootstrap 5
* Reactive Forms
* HttpClient
* Angular Signals
* REST API

---

# 🏗️ Estrutura do Projeto

```text
src/app/

├── app.ts
├── app.html
├── app.css
├── app.config.ts
└── app.routes.ts
```

---

# 🔗 Integração com Backend

Esta aplicação consome a **API Clientes**, disponível em:

➡️ https://github.com/beatrizlima-tech/api-clientes

Durante o desenvolvimento, a API é executada localmente através do endereço:

```text
http://localhost:8081/api/v1/clientes
```

---

# 🔗 Endpoints Consumidos

| Método | Endpoint                  | Descrição           |
| ------ | ------------------------- | ------------------- |
| POST   | `/api/v1/clientes`        | Cadastro de cliente |
| GET    | `/api/v1/clientes/{nome}` | Consulta por nome   |
| PUT    | `/api/v1/clientes/{id}`   | Atualização         |
| DELETE | `/api/v1/clientes/{id}`   | Exclusão lógica     |

---

# ⚙️ Como Executar

## 1. Clone o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-clientes.git
```

---

## 2. Instale as dependências

```bash
npm install
```

---

## 3. Execute a API Clientes

Certifique-se de iniciar o backend antes de executar o frontend:

```text
https://github.com/beatrizlima-tech/api-clientes
```

---

## 4. Execute a aplicação

```bash
ng serve
```

---

## 5. Acesse

```text
http://localhost:4200
```

---

# 📊 Arquitetura

```text
Usuário
    │
    ▼
Angular 21
    │
    ▼
HttpClient
    │
    ▼
API Clientes (Spring Boot)
    │
    ▼
PostgreSQL
```

---

# 📚 Conceitos Aplicados

* Angular Standalone Components
* Componentização
* CRUD
* Reactive Forms
* Angular Signals
* HttpClient
* Consumo de APIs REST
* Comunicação Frontend e Backend
* Responsividade com Bootstrap
* Organização em camadas

---

# 📌 Melhorias Futuras

* Implementar paginação
* Adicionar filtros avançados de pesquisa
* Melhorar validações visuais dos formulários
* Exibir mensagens utilizando Toasts
* Implementar indicador de carregamento (Loading)
* Criar testes automatizados
* Melhorar a experiência em dispositivos móveis

---

# 👩‍💻 Autora

Desenvolvido por **Beatriz Lima**

🔗 GitHub
https://github.com/beatrizlima-tech

💼 LinkedIn
https://www.linkedin.com/in/beatrizlima-tech
