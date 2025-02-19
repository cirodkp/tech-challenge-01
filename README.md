# Projeto Tech Challenge 01 - .NET 8 + Postgres com Docker 

Este é um projeto .NET que utiliza Docker para facilitar o ambiente de desenvolvimento e execução. Utiliza Docker Compose para orquestrar a aplicação juntamente com um banco de dados PostgreSQL.

## Pré-requisitos

- Docker Engine: [Instalação do Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Instalação do Docker Compose](https://docs.docker.com/compose/install/)

## Como executar

1. Clone este repositório:

 ```bash
   git clone [https://github.com/cirodkp/tech-challenge-01.git]
   cd tech-challenge-01
  ```

2. Execute o seguinte comando para iniciar o projeto junto com o PostgreSQL:

```bash
  docker-compose up -d
```
Isso iniciará os contêineres Docker em segundo plano (-d para detached mode), incluindo a aplicação .NET e o banco de dados PostgreSQL.

Acesse a aplicação em http://localhost:8080

Usuário e senha para a geração de Token. Usuário:admin, senha: admin@123

3. Parando a execução do projeto e removendo os containers

```bash
  docker-compose down
```
