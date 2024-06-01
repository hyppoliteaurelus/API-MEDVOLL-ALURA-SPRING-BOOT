# Projeto API MedVoll

## Descrição

Este projeto é uma API RESTful para gerenciar médicos e seus respectivos dados. Ele utiliza Spring Boot, Spring Data JPA e um banco de dados relacional. A API permite cadastrar médicos, atualizar informações, listar médicos e obter detalhes de um médico específico.

## Tecnologias Utilizadas

- Java 17
- Spring Boot 2.7.x
- Spring Data JPA
- Hibernate
- Banco de Dados H2 (para desenvolvimento e testes)
- Lombok
- Maven

## Clone o Repositório:
git clone https://github.com/seu-usuario/projeto-medvoll.git
cd projeto-medvoll

## Estrutura do Projeto

```plaintext
src/
├── main/
│   ├── java/
│   │   └── api/
│   │       ├── Controller/
│   │       │   ├── HelloController.java
│   │       │   └── MedicoController.java
│   │       ├── endereco/
│   │       │   ├── DadosEndereco.java
│   │       │   └── Endereco.java
│   │       └── medico/
│   │           ├── DadosAtualizacaoMedico.java
│   │           ├── DadosCadstroMedico.java
│   │           ├── DadosListagemMedico.java
│   │           ├── Especialidade.java
│   │           ├── Medico.java
│   │           └── MedicoRepository.java
│   └── resources/
│       └── application.properties
└── test/
    ├── java/
    └── api/
        └── Controller/
            └── MedicoControllerTest.java
