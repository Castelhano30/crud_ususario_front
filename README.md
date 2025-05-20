# Front-end CRUD de Usuários

Este projeto é um front-end simples desenvolvido com React e Vite, utilizando Axios para integração com o backend criado em Node.js. O objetivo deste projeto é demonstrar um CRUD (Create, Read, Update, Delete) básico de usuários, permitindo visualizar a lista de usuários, criar novos usuários e deletar usuários existentes.

## Tecnologias utilizadas

* **React**: Biblioteca JavaScript para construção da interface.
* **Vite**: Ferramenta moderna e rápida para desenvolvimento de projetos React.
* **Axios**: Biblioteca para realizar requisições HTTP ao backend.

## Funcionalidades implementadas

### Visualização dos usuários

* Exibe um array contendo todos os usuários cadastrados.

### Criação de usuário

* Formulário simples com campos para `name`, `age` e `email`.
* Ao submeter o formulário, um novo usuário é adicionado ao banco de dados.

### Exclusão de usuário

* Cada usuário listado possui um botão para deletá-lo.
* Ao clicar no botão, o usuário é removido da lista e do banco de dados.

## Integração com backend

* O front-end está conectado com um backend desenvolvido com Node.js, Express e Prisma.
* Todas as operações (criação, leitura e exclusão) refletem diretamente no banco de dados configurado no backend.

## Como executar o projeto

Siga os passos abaixo para executar o front-end localmente:

### Clone o repositório

```bash
git clone <url_do_repositorio>
```

### Instale as dependências

```bash
cd nome-do-projeto
npm install
```

### Execute o projeto

```bash
npm run dev
```

O front-end estará disponível na URL `http://localhost:5173`.

Certifique-se de que o backend esteja em execução para garantir o correto funcionamento das requisições HTTP.
