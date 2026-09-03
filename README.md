<div align="center">

# 📚 API de Livros

### João Gabriel Tavares de Lira

<img src="joaogblira.png" alt="Foto de João Gabriel Tavares de Lira" width="160" style="border-radius: 50%;" />

**Projeto da disciplina de SW-II (Sistemas Web II) · 3º Bimestre**

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?logo=apache&logoColor=white)](https://www.apachefriends.org/)
[![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=111111)](https://developer.mozilla.org/docs/Web/JavaScript)

</div>

---

## 📖 Sobre o projeto

Este repositório reúne o desenvolvimento da minha **API de Livros**, atividade avaliativa do 3º Bimestre da disciplina de SW-II (Sistemas Web II), na Etec Professora Maria Cristina Medeiros, turma 3C.

O projeto consiste em uma aplicação completa para **gerenciamento de livros**, construída em quatro etapas: começando pelo banco de dados e pela API em Python, e terminando em uma interface web funcional no navegador, onde é possível cadastrar, listar, editar e excluir livros.

Cada livro cadastrado possui os seguintes dados:

| Campo | Descrição |
| --- | --- |
| `id` | Identificador único |
| `titulo` | Título do livro |
| `autor` | Autor do livro |
| `ano_publicacao` | Ano de publicação |
| `disponivel` | Situação de disponibilidade |

## 🎯 Objetivo

O objetivo final é entregar uma aplicação funcional de ponta a ponta, com:

- uma **API REST** feita em FastAPI, com CRUD completo (`Create`, `Read`, `Update`, `Delete`);
- um **banco de dados MySQL**, administrado pelo phpMyAdmin (via XAMPP);
- uma **interface web** em HTML, CSS e JavaScript, que consome a API usando `fetch`;
- validação de dados e tratamento de erros HTTP;
- um histórico organizado de commits no GitHub, documentando a evolução do projeto etapa por etapa.

Além do resultado final, o projeto também é uma forma de praticar conceitos importantes de desenvolvimento web: comunicação entre front-end e back-end, modelagem de banco de dados, boas práticas de código e uso do Git/GitHub como ferramenta de versionamento.

## 🛠️ Como vai ser feito

O desenvolvimento segue quatro etapas, feitas em sala de aula, uma por vez:

### 🟦 Etapa 1 · Fundação
Preparação do ambiente de desenvolvimento, instalação das dependências, criação do banco `biblioteca_db` no MySQL e conexão da API com o banco através de uma rota de saúde (health check).

### 🟩 Etapa 2 · Modelo e consultas
Criação do modelo `Livro`, dos schemas de validação, da sessão do banco de dados e das rotas `POST` (cadastrar) e `GET` (listar/consultar).

### 🟧 Etapa 3 · CRUD completo
Implementação das rotas `PUT` (atualizar) e `DELETE` (excluir), com tratamento de erros e testes de todas as operações do CRUD.

### 🟥 Etapa 4 · Front End
Construção da interface web em HTML, CSS e JavaScript, consumindo a API para cadastrar, listar, editar e excluir livros diretamente pelo navegador.

## 🔁 CRUD

| Símbolo | Operação | Ação |
| --- | --- | --- |
| 🟢 | **Create** | Cadastrar livros |
| 🔵 | **Read** | Listar e consultar livros |
| 🟠 | **Update** | Atualizar livros |
| 🔴 | **Delete** | Excluir livros |

## 🧱 Stack utilizada

`Python` · `FastAPI` · `Uvicorn` · `SQLAlchemy` · `PyMySQL` · `MySQL` · `XAMPP` · `phpMyAdmin` · `HTML` · `CSS` · `JavaScript` · `VS Code` · `GitHub`

> O arquivo `database/biblioteca_db.sql` fica versionado neste repositório, permitindo recriar o banco a qualquer momento pelo phpMyAdmin.

## 📅 Andamento

| Etapa | Entrega | Data | Status |
| --- | --- | --- | --- |
| 🟦 1 · Fundação | Ambiente e conexão | 03/09/2026 | ⏳ Em andamento |
| 🟩 2 · Modelo | `POST`/`GET` | 10/09/2026 | 🔒 A fazer |
| 🟧 3 · CRUD | `PUT`/`DELETE` | 17/09/2026 | 🔒 A fazer |
| 🟥 4 · Front End | Interface Web | 24/09/2026 | 🔒 A fazer |

## 🚀 Como rodar o projeto

```bash
# clonar o repositório
git clone <url-do-repositorio>
cd api-de-livros

# criar e ativar o ambiente virtual
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Linux/Mac

# instalar as dependências
pip install -r requirements.txt

# criar o arquivo .env com os dados de conexão do MySQL local
# (não incluído no repositório por segurança)

# iniciar Apache e MySQL pelo XAMPP
# importar database/biblioteca_db.sql pelo phpMyAdmin

# rodar a API
uvicorn main:app --reload
```

> 🔒 O arquivo `.env` não é versionado, pois contém a senha local do MySQL.

<div align="center">

**📚 API de Livros · João Gabriel Tavares de Lira · SW-II · 3º Bimestre**

</div>
