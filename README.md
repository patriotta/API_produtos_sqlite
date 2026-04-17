# 🚀 API REST de Produtos com SQLite

## 📌 Descrição

Esta é uma API REST desenvolvida em Node.js utilizando Express e SQLite como banco de dados.
Permite realizar operações completas de CRUD (Create, Read, Update, Delete) para gerenciamento de produtos.

---

## 🛠️ Tecnologias utilizadas

* Node.js
* Express
* SQLite (better-sqlite3)
* Postman

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/API_produtos_sqlite.git
```

### 2. Entrar na pasta

```bash
cd API_produtos_sqlite
```

### 3. Instalar dependências

```bash
npm install
```

### 4. Rodar o servidor

```bash
node index.js
```

Servidor rodando em:

```
http://localhost:3000
```

---

## 📦 Endpoints da API

### 🔹 Listar produtos

GET /produtos

---

### 🔹 Buscar produto por ID

GET /produtos/:id

---

### 🔹 Criar produto

POST /produtos

Exemplo:

```json
{
  "nome": "Notebook",
  "preco": 3500
}
```

---

### 🔹 Atualizar produto

PUT /produtos/:id

```json
{
  "nome": "Produto Atualizado",
  "preco": 999
}
```

---

### 🔹 Deletar produto

DELETE /produtos/:id

---

## 🔍 Filtros, ordenação e paginação

### 📌 Filtrar por preço mínimo

```
/produtos?minPreco=500
```

### 📌 Paginação

```
/produtos?page=1&limit=5
```

### 📌 Ordenação

```
/produtos?order=desc
```

---

## 📊 Banco de dados

* Banco: SQLite
* Arquivo: banco.db
* Tabela: produtos
* Contém mais de 20 registros cadastrados

---

## 📮 Testes da API

Os testes foram realizados utilizando o Postman.

### 📎 Collection

A collection do Postman está disponível no projeto (arquivo `.json`).

---

## 👨‍💻 Autor

Gabriel Patriota
