# 👥 Web Clientes

![Angular](https://img.shields.io/badge/Angular-20-red?style=for-the-badge\&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge\&logo=bootstrap)
![REST API](https://img.shields.io/badge/REST%20API-Integration-blue?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

## 📌 Sobre o projeto

O **Web Clientes** é uma aplicação frontend desenvolvida com **Angular** para gerenciamento de clientes, consumindo uma API REST criada com **Java** e **Spring Boot**.

A aplicação permite cadastrar, consultar, editar e excluir clientes por meio de uma interface web responsiva, utilizando formulários reativos, requisições HTTP e integração completa com backend.

---

## 🚀 Funcionalidades

* ✅ Cadastro de clientes
* ✅ Consulta de clientes por nome
* ✅ Edição de clientes
* ✅ Exclusão de clientes
* ✅ Integração com API REST
* ✅ Formulários reativos
* ✅ Consumo de endpoints com HttpClient
* ✅ Interface com Bootstrap
* ✅ Controle de estado com Signals

---

## 🧱 Tecnologias Utilizadas

* Angular
* TypeScript
* Bootstrap
* HTML5
* CSS3
* Reactive Forms
* HttpClient
* Signals
* REST API

---

## 🏗️ Estrutura do Projeto

```text
src/app/

├── app.html
├── app.css
├── app.ts
├── app.config.ts
└── app.routes.ts
```

---

## 🔗 Integração com Backend

Este frontend consome a API Clientes:

```text
http://localhost:8081/api/v1/clientes
```

Projeto relacionado:

```text
https://github.com/beatrizlima-tech/api-clientes
```

---

## 🔗 Endpoints Consumidos

| Método | Endpoint                  | Descrição          |
| ------ | ------------------------- | ------------------ |
| POST   | `/api/v1/clientes`        | Cadastrar cliente  |
| GET    | `/api/v1/clientes/{nome}` | Consultar clientes |
| PUT    | `/api/v1/clientes/{id}`   | Atualizar cliente  |
| DELETE | `/api/v1/clientes/{id}`   | Excluir cliente    |

---

## ⚙️ Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-clientes.git
```

---

### 2. Instalar dependências

```bash
npm install
```

---

### 3. Executar o backend

Antes de iniciar o frontend, execute a API Clientes:

```text
https://github.com/beatrizlima-tech/api-clientes
```

---

### 4. Executar o frontend

```bash
ng serve
```

---

### 5. Acessar no navegador

```text
http://localhost:4200
```

---

## 📊 Arquitetura

```text
Usuário
   │
   ▼
Web Clientes (Angular)
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

## 📌 Melhorias Futuras

* [ ] Adicionar validações visuais nos formulários
* [ ] Exibir mensagens de sucesso e erro com componentes visuais
* [ ] Criar layout mais moderno para a tabela
* [ ] Implementar paginação
* [ ] Implementar loading durante requisições
* [ ] Melhorar responsividade mobile
* [ ] Criar testes automatizados
* [ ] Ajustar testes padrão do Angular

---

## 👩‍💻 Autora

**Beatriz Lima de Oliveira**

🔗 GitHub:
https://github.com/beatrizlima-tech
