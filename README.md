# Sistema de Gestão de Contatos - Desafio Muralis

Este projeto foi desenvolvido como parte do desafio para o Programa de Estágio da Muralis. Se trata de um sistema de gestão de contatos para a empresa fictícia Comércio S.A., permitindo o cadastro de clientes e seus respectivos contatos.

## Visão Geral

A solução foi desenvolvida com uma arquitetura cliente-servidor, dividida em duas partes principais:

- **Frontend**: Interface de usuário desenvolvida com HTML, CSS, JavaScript e React
- **Backend**: API RESTful desenvolvida com Java e Spring Boot

## Repositórios

O projeto está dividido em três repositórios:

- Repositório Principal (o presente repositório): Documentação geral e integração
- [Repositório Backend](https://github.com/thomasmfx/gestao-contatos-backend) - API RESTful
- [Repositório Frontend](https://github.com/thomasmfx/gestao-contatos-frontend) - Interface do usuário

## Funcionalidades Implementadas

### Requisitos funcionais

- [x]  RF01: O sistema deve permitir o cadastro de clientes com os seguintes dados: Nome,
CPF, Data de Nascimento e Endereço;
- [x]  RF02: O sistema deve permitir a edição dos dados de um cliente cadastrado;
- [x]  RF03: O sistema deve permitir a exclusão de um cliente cadastrado;
- [x]  RF04: O sistema deve permitir a listagem de todos os clientes cadastrados;
- [x]  RF05: O sistema deve permitir a busca de um cliente pelo Nome ou CPF;
- [x]  RF06: O sistema deve permitir o cadastro de contatos para um cliente, contendo os seguintes dados: Tipo do Contato (Telefone, E-mail), Valor do Contato (número ou e-
mail) e Observação;
- [x]  RF07: O sistema deve permitir a edição dos contatos de um cliente;
- [x]  RF08: O sistema deve permitir a exclusão de um contato de um cliente;
- [x]  RF09: O sistema deve permitir a listagem de todos os contatos de um cliente
específico.

### Regras de Negócio

- [x]  RN01: Os campos Nome e CPF são obrigatórios no cadastro do cliente;
- [x]  RN02: Os campos Tipo do Contato e Valor do Contato são obrigatórios no cadastro do contato;
- [x]  RN03: O CPF informado deve ser único no sistema;
- [x]  RN04: O Nome do cliente não pode estar vazio;
- [x]  RN05: A Data de Nascimento deve ser válida;
- [x]  RN06: Um cliente pode ter mais de um contato cadastrado;
- [x]  RN07: Ao excluir um cliente, todos os seus contatos devem ser removidos do sistema;
- [x]  RN08: O sistema deve validar os dados informados antes de permitir o cadastro ou edição.

## Configuração do Ambiente

Para executar o projeto completo, siga estas etapas:

1. Clone os repositórios em seu local de preferência:
```bash
git clone https://github.com/thomasmfx/gestao-contatos-backend.git
git clone https://github.com/thomasmfx/gestao-contatos-frontend.git
```

2. Configure e inicie o backend (detalhes no README do backend)
3. Configure e inicie o frontend (detalhes no README do frontend)

## Tecnologias Utilizadas

### Frontend

- HTML
- CSS
- JavaScript
- React

### Backend

- Java 
- Spring Boot
- Maven
- Hibernate

### Banco de Dados

- PostgreSQL

<!-- ## Vídeo Demonstrativo

Um vídeo demonstrativo da execução do sistema pode ser encontrado [neste link](). -->