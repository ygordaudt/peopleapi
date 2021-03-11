<h2>Sistema de gerenciamento de pessoas desenvolvido em API REST com o framework Spring Boot e hospedagem no Heroku</h2>

Este sistema foi desenvolvido com o intuito de estudar as referidas tecnologias de Java e para apresentação de projeto
no BootCamp FULLSTACK da Everis, a partir da plataforma Digital Innovation One.

O presente material conta com os seguintes itens:

* Modelo de dados para o mapeamento de entidades em bancos de dados;
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema);
* Relação de cada uma das operações acima com o padrão arquitetural REST;
* Desenvolvimento de testes unitários para validação das funcionalidades;
* Implantação do sistema na nuvem através do Heroku (https://yd-peopleapi-live.herokuapp.com/).

Dentre as dependências importadas pelo Spring (https://start.spring.io), temos as seguintes:
* Spring Boot DevTools (DevTools)
* Lombok (DevTools)
* Spring Web (Web)
* Spring Boot Actuator (OPS)
* Spring Data JPA (SQL)
* H2 Database (SQL)

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```


São necessários os seguintes pré-requisitos para a execução do projeto:

* Java 11 ou versões superiores;
* Maven 3.6.3 ou versões superiores;
* Intellj IDEA Community Edition ou outra IDE qualquer;
* Conta no Heroku para o deploy do projeto na nuvem.

Abaixo, seguem links utilizados no decorrer do estudo:

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial do Spring Initialzr, para setup do projeto](https://start.spring.io/)
* [Site oficial do Heroku](https://www.heroku.com/)
* [Site oficial do GIT](https://git-scm.com/)
* [Site oficial do GitHub](http://github.com/)
* [Documentação oficial do Lombok](https://projectlombok.org/)
* [Documentação oficial do Map Struct](https://mapstruct.org/)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)


