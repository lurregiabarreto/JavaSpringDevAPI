# JavaSpringDevAPI

## Descrição

O **JavaSpringDevAPI** é uma API RESTful desenvolvida utilizando Java 17 e Spring Boot 3. Este projeto tem como objetivo demonstrar a construção de uma aplicação robusta e escalável com tecnologias modernas, integrando uma documentação completa com OpenAPI (Swagger).

## Tecnologias Utilizadas

- **Java 17**: Linguagem de programação robusta e amplamente utilizada, aproveitando suas mais recentes funcionalidades.
- **Spring Boot 3**: Framework que maximiza a produtividade por meio da autoconfiguração e modularidade.
- **Spring Data JPA**: Facilita o acesso a dados em bancos de dados relacionais, proporcionando uma interface simples e intuitiva.
- **OpenAPI (Swagger)**: Ferramenta para documentação da API, proporcionando uma interface clara e interativa para testar os endpoints.

## Funcionalidades

- Endpoints para CRUD de recursos principais.
- Documentação automática da API com Swagger.
- Integração com banco de dados SQL utilizando Spring Data JPA.
- Deploy contínuo e monitoramento na nuvem com Railway.

## Documentação da API

A documentação completa da API pode ser acessada pelo Swagger:

[Documentação Swagger](https://sdw-2023-prd.up.railway.app/swagger-ui.html)

## Diagrama de Classes

O diagrama de classes para o domínio da API pode ser encontrado no Figma, utilizado para abstração e análise do projeto.

## Como Executar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/lurregiabarretp/JavaSpringDevAPI.git
   ```

2. Entre na pasta do projeto:
   ```bash
   cd JavaSpringDevAPI
   ```

3. Configure o banco de dados no arquivo `application.properties` com suas credenciais e URL.

4. Execute a aplicação:
   ```bash
   ./mvnw spring-boot:run
   ```

5. Acesse a documentação da API localmente:
   ```
   http://localhost:8080/swagger-ui.html
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para clonar, modificar, e propor melhorias para este projeto. Se divulgar sua versão, não esqueça de mencionar o projeto original! 😊

