# API REST - Cadastro de Usuários

API REST para gerenciamento de usuários, desenvolvida em Java com Spring Boot, utilizando H2 como banco de dados em memória. Seguindo uma arquitetura organizada entre as camadas de Controller, Business e Infrastructure, o sistema implementa operações CRUD para manipulação de nome e e-mail com foco em fundamentos didáticos e código limpo.

## Documentação no Postman
https://documenter.getpostman.com/view/48074793/2sBXc7MkKx

## Tecnologias
* Java
* Spring Boot
* Spring Data JPA
* H2 Database
* Lombok
* Maven

## Estrutura do Projeto
* **Controller**: Camada de exposição da API e definição dos endpoints.
* **Business**: Camada responsável pela lógica de negócio e regras da aplicação.
* **Infrastructure**: Responsável pela persistência de dados (Entities e Repositories).

## Exemplo de JSON (Body da Requisição)
```json
{
  "nome": "Seu Nome",
  "email": "exemplo@email.com"
}
```

## Autor
[Marcelo Vieira](<https://www.linkedin.com/in/marcelovieirasilva/>)
