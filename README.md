# API para Gerenciamento de Pessoas

Instruções
Crie uma API para o sistema de gerenciamento de pessoas de uma universidade:

- *A única entidade da aplicação é Pessoa, que contém nome, cpf e idade.*
- *Utilize como base de dados o Mysql. Variáveis de conexão com o banco:*

spring.datasource.url=jdbc:mysql://localhost:3306/nome_da_base spring.datasource.username=root spring.datasource.password=senha spring.jpa.hibernate.ddl-auto=update

Crie um projeto Spring utilizando o Spring Initializr (https://start.spring.io/), adicionando as dependências Spring Web, JPA, MySql e Lombok.

## A solução deve conter:
   Uma classe Entity para representar a tabela Pessoa da base de dados;
   Uma classe Repositório;
   Uma classe Controlador;
   Uma classe DTO.
   
A API deve conter um método POST para criar uma Pessoa na base e um método GET Pessoa por Id para retornar a Pessoa com o id informado.

---
## UNINASSAU
Disciplina: Back-end
---
## Alunos : 

Felipe Guizzi - 01593732

Rayane Silva - 01203448
