# Sistema de Gerenciamento de Farmácia
Este repositório contém o backend de um sistema de gerenciamento de farmácia. O projeto inclui funcionalidades completas de CRUD (Create, Read, Update, Delete) para Categorias e Produtos, autenticação e segurança com tokens JWT, testes unitários e documentação abrangente.

## Funcionalidades

- <b>CRUD de Categorias</b>: Adicionar, visualizar, atualizar e deletar categorias de produtos.
- <b>CRUD de Produtos</b>: Adicionar, visualizar, atualizar e deletar produtos.
- <b>Autenticação e Segurança</b>: Implementação de segurança com tokens JWT para autenticação de usuários.
- <b>Testes Unitários</b>: Cobertura de testes unitários para garantir a qualidade e funcionamento do sistema.
- <b>Documentação</b>: Documentação completa da API utilizando Swagger.

## Tecnologias Utilizadas

- <b>Java</b>: Linguagem de programação principal utilizada no projeto.
- <b>Spring Boot</b>: Framework para construção de aplicações Java.
- <b>Spring Security</b>: Para implementação da segurança e autenticação.
- <b>JWT (JSON Web Token)</b>: Para autenticação baseada em tokens.
- <b>MySQL</b>: Banco de dados utilizado para armazenar informações.
- <b>JUnit</b>: Framework para testes unitários.
- <b>Swagger</b>: Ferramenta para documentação da API.

## Como Executar o Projeto

### Pré-requisitos

- Java 11 ou superior instalado
- Maven instalado
- MySQL instalado e configurado

### Passos para Execução

1. Clone o Repositório

```
git clone https://github.com/eduardowada/CRUD-Farmacia.git
cd CRUD-Farmacia
```

2. Configurar o Banco de Dados

- Crie um banco de dados MySQL.
- Atualize o arquivo application.properties com as configurações do seu banco de dados.

```
spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

3. Build e Execute a Aplicação

```
spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

### Documentação da API

```
http://localhost:8080/swagger-ui.html
```

### Estrutura do Projeto

```
src/
├── main/
│   ├── java/com/generation/farmacia/
│   │   ├── controller/      # Controladores REST
│   │   ├── model/           # Modelos de Dados
│   │   ├── repository/      # Repositórios
│   │   ├── security/        # Configurações de Segurança
│   │   ├── service/         # Serviços de Negócio
│   │   └── FarmaciaApplication.java  # Classe Principal
│   └── resources/
│       ├── application.properties  # Configurações da Aplicação
└── test/
    └── java/com/generation/farmacia/  # Testes Unitários
```
