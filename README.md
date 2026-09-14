# Snippetbox

Aplicação web desenvolvida em Go como parte dos estudos acompanhando o livro **Let's Go**, de Alex Edwards.

O projeto acompanha a construção de uma aplicação web utilizando principalmente os recursos da biblioteca padrão do Go, explorando conceitos de HTTP, servidores web, roteamento, handlers e templates.

> 🚧 **Em desenvolvimento:** novos conceitos e funcionalidades serão adicionados conforme o avanço no livro.

## Conceitos explorados

- Servidores HTTP com net/http
- http.ServeMux
- Handlers e http.Handler
- Rotas e endpoints
- Métodos HTTP
- Templates HTML
- Estruturação de aplicações Go
- Packages e módulos

## Tecnologias

- Go
- `net/http`
- HTML Templates
- Git

## Executando o projeto

Clone o repositório:

```bash
git clone https://github.com/lucasvsclls/snippetbox
```

Acesse o diretório:

```bash
cd snippetbox
```

Execute a aplicação:

```bash
go run ./cmd/web
```

O servidor será iniciado em `http://localhost:4000`.

Acesse um dos endpoints disponíveis no navegador, por exemplo:

```text
http://localhost:4000/
```

## Objetivo

O projeto tem como objetivo desenvolver uma base prática em desenvolvimento backend com Go, acompanhando progressivamente os conceitos apresentados no livro **Let's Go** e aplicando-os na construção de uma aplicação web.

## Referência

Projeto desenvolvido acompanhando o livro:

**Let's Go — Alex Edwards**
