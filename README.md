# QA Study - ShortBeyond Aplicação Encurtadora de URLs

Este projeto faz parte dos meus estudos em Quality Assurance (QA), onde irei realizar testes manuais e criar testes automatizados para a aplicação WEB e API do projeto shortBeyond. Esta aplicação é um encurtador de URLs que possibilita que usuários gerenciem e criem URLs personalizadas, oferecendo funcionalidades como geração de links curtos.

## Sobre o Projeto

O shortBeyond é uma aplicação simples para encurtar URLs, com funcionalidades como geração de links curtos e autenticação via JWT. Ele usa uma arquitetura containerizada com Docker Compose, incluindo:

- Banco de dados PostgreSQL para armazenar dados;
- Adminer para gerenciamento do banco via web;
- API backend em Node.js para lógica de negócios;
- Frontend web para interface do usuário.

O foco deste repositório é testar a aplicação, e adquirir conhecimentos a respeito de testes e automações de APIs.

## Tecnologias

- NodeJS
- TypeScript
- Docker
- Bruno
- Playwright
- PostgreSQL

## Como executar

### Pré-requisitos

1. **Docker Desktop** - Instale o Docker Desktop em sua máquina
2. **WSL2** - Configure o WSL2 (Windows Subsystem for Linux) para compatibilidade com Docker

### Executando a aplicação

Após a instalação dos pré-requisitos, execute o seguinte comando na raiz do projeto:

```bash
docker compose up -d
```

Este comando irá:
- Baixar as imagens necessárias (PostgreSQL, Adminer, API e Web)
- Criar e iniciar todos os containers
- Configurar a rede interna entre os serviços
- Executar todos os serviços em background (`-d`)

### Acessando os serviços

- **Frontend Web**: http://localhost
- **API**: http://localhost:3333
- **Adminer (Banco de dados)**: http://localhost:8080
- **PostgreSQL**: localhost:5432

## Testes

```bash
# Como executar os testes
```