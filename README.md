# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/GuilhermeAraujo7/dslist/blob/main/LICENSE) 

# Sobre o projeto

DSList se consiste em uma aplicação back-end, resultado do trabalho realizado durante o Intensivão Java Spring, um evento promovido pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

Essa aplicação tem como objetivo principal possibilitar aos usuários a pesquisa e obtenção de informações sobre uma variedade de jogos.
Os usuários têm a capacidade de realizar consultas com base em diferentes critérios, como gênero e classificação dos jogos. Além disso, a aplicação oferece uma funcionalidade especial que permite a personalização da forma como a lista de jogos é apresentada, tornando a experiência do usuário mais flexível e adaptável.

## Modelo conceitual

![App Screenshot](https://github.com/GuilhermeAraujo7/dslist/blob/main/assets/dslist-model.png)

## End Points
- `GET games`: Busca a lista de jogos
- `GET games by id`: Busca um jogo por meio de ID
- `GET games lists`: Busca a categoria das listas de jogos
- `GET games by lists`: Busca uma lista por meio de seu ID mostrando quais jogos estão dentro desta categoria
- `POST list replacement`: Organiza a lista como o usuário preferir

## Retorno da API
![App Screenshot](https://github.com/GuilhermeAraujo7/dslist/blob/main/assets/return-api-end-point.png)

# Tecnologias utilizadas

## Back end
- Java
- Spring Boot
- H2 Console
- JPA / Hibernate
- Maven

## Implantação em produção
- Banco de dados: Postgresql

# Como executar o projeto

Pré-requisitos: Java 17


```bash
# clonar repositório
git clone https://github.com/GuilhermeAraujo7/dslist-backend

# entrar na pasta do projeto back end
cd dslist-backend

# executar o projeto
./mvnw spring-boot:run
```


# Autor

Guilherme Henrique de Araujo
