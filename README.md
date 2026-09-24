<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:009688,100:4479A1&height=200&section=header&text=API%20de%20Livros&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Sistemas%20Web%20II%20·%203º%20Bimestre&descAlignY=55&descSize=18" width="100%"/>

### João Gabriel Tavares de Lira

<img src="assets/joagablira.jpg"  width="160" style="border-radius: 50%; box-shadow: 0 0 20px rgba(0,150,136,0.5);" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=009688&center=true&vCenter=true&width=600&lines=Cadastre%2C+liste%2C+edite+e+exclua+livros;API+REST+com+FastAPI+%2B+MySQL;Front-end+consumindo+a+API+com+fetch" alt="Typing SVG" />

<br/>

## 🧱 Stack utilizada

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,mysql,html,css,js,vscode,git,github" />

</div>

`Python` · `FastAPI` · `Uvicorn` · `SQLAlchemy` · `PyMySQL` · `MySQL` · `XAMPP` · `phpMyAdmin` · `HTML` · `CSS` · `JavaScript` · `VS Code` · `GitHub`

<img src="assets/livros-animado.svg" width="100%"> </div>

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

<div align="center">

<img src="assets/livros-divisor.svg" width="100%">

</div>

## 🎯 Objetivo

O objetivo final é entregar uma aplicação funcional de ponta a ponta, com:

- 🟢 uma **API REST** feita em FastAPI, com CRUD completo (`Create`, `Read`, `Update`, `Delete`);
- 🔵 um **banco de dados MySQL**, administrado pelo phpMyAdmin (via XAMPP);
- 🟠 uma **interface web** em HTML, CSS e JavaScript, que consome a API usando `fetch`;
- 🔴 validação de dados e tratamento de erros HTTP;
- 📌 um histórico organizado de commits no GitHub, documentando a evolução do projeto etapa por etapa.

Além do resultado final, o projeto também é uma forma de praticar conceitos importantes de desenvolvimento web: comunicação entre front-end e back-end, modelagem de banco de dados, boas práticas de código e uso do Git/GitHub como ferramenta de versionamento.

## 🛠️ Como vai ser feito

O desenvolvimento segue quatro etapas, feitas em sala de aula, uma por vez:

<table>
<tr>
<td width="25%" align="center">

### 🟦
**Etapa 1**
<br/>Fundação

Preparação do ambiente, instalação das dependências, criação do banco `biblioteca_db` e conexão da API via rota de *health check*.

</td>
<td width="25%" align="center">

### 🟩
**Etapa 2**
<br/>Modelo e consultas

Criação do modelo `Livro`, schemas de validação, sessão do banco e rotas `POST` / `GET`.

</td>
<td width="25%" align="center">

### 🟧
**Etapa 3**
<br/>CRUD completo

Rotas `PUT` / `DELETE`, tratamento de erros e testes de todas as operações do CRUD.

</td>
<td width="25%" align="center">

### 🟥
**Etapa 4**
<br/>Front End

Interface web em HTML, CSS e JavaScript, consumindo a API para cadastrar, listar, editar e excluir livros.

</td>
</tr>
</table>

## 🔁 CRUD

| Símbolo | Operação | Ação |
| --- | --- | --- |
| 🟢 | **Create** | Cadastrar livros |
| 🔵 | **Read** | Listar e consultar livros |
| 🟠 | **Update** | Atualizar livros |
| 🔴 | **Delete** | Excluir livros |



> 💾 O arquivo `database/biblioteca_db.sql` fica versionado neste repositório, permitindo recriar o banco a qualquer momento pelo phpMyAdmin.

<div align="center">

<img src="assets/livros-divisor.svg" width="100%">

</div>

## 📅 Andamento

<div align="center">

### 📊 Progresso geral do projeto

![Progresso](https://img.shields.io/badge/Progresso-100%25-009688?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Finalizado-success?style=for-the-badge)

### 🏆 PROJETO FINALIZADO COM SUCESSO!

</div>

| Etapa | Entrega | Data | Status |
| --- | --- | --- | --- |
| 🟦 1 · Fundação | Ambiente e conexão | 03/09/2026 | ☑️ Concluído |
| 🟩 2 · Modelo | `POST` / `GET` | 10/09/2026 | ☑️ Concluído |
| 🟧 3 · CRUD | `PUT` / `DELETE` | 17/09/2026 | ☑️ Concluído |
| 🟥 4 · Front End | Interface Web | 24/09/2026 | ☑️ Concluído |

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4479A1,100:009688&height=120&section=footer"/>

**📚 API de Livros · João Gabriel Tavares de Lira · SW-II · 3º Bimestre**

</div>

