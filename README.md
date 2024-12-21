# DynamoDB
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/WelingtonFranzoso/franzoso-agregador-de-investimentos/blob/main/LICENSE) 

# Sobre o projeto

Este projeto é uma aplicação CRUD para gerenciamento de pontuação de jogos. Utilizando a solução de emulação da AWS Localstack e o banco de dados NoSQL DynamoDB, o sistema permite armazenar e gerenciar as pontuações de jogos com base em um username como partition key, game id como sort key e o score (pontuação) fornecido no corpo da requisição.

A aplicação tem como objetivo principal fornecer uma interface simples para registrar, consultar, atualizar e excluir pontuações de diferentes jogos.

# Funcionalidades
- Create (Criar): Registrar a pontuação de um jogador para um jogo específico.
- Read (Ler): Consultar a pontuação de um jogador em um jogo específico.
- Update (Atualizar): Alterar a pontuação de um jogador em um jogo específico.
- Delete (Excluir): Remover a pontuação de um jogador para um jogo específico.

# Tecnologias utilizadas
- Java: Linguagem de programação principal.
- Spring Boot: Framework para criação de aplicações Java.
- Maven: Gerenciador de dependências e construção do projeto.
- Docker: Containerização da aplicação para facilitar a execução e deployment.
- DynamoDB: Banco de dados NoSQL da AWS para armazenamento de dados.
- Localstack: Emulação local dos serviços da AWS.
- AWS CLI: Para interação com o DynamoDB e outros serviços da AWS.

# Como executar o projeto

## Back end
### Pré-requisitos: 
- Java 17
- Maven
- Docker
- DynamoDB(local ou via Docker)
- AWS Localstack

```bash
# clonar repositório
git clone git@github.com:WelingtonFranzoso/dynamodb.git

# entrar na pasta do projeto back end
cd dynamodb

# executar localstack
localstack start

# executar o projeto
./mvnw spring-boot:run
```

# Autor

Welington Franzoso
https://www.linkedin.com/in/welington-franzoso-88a8301b9
