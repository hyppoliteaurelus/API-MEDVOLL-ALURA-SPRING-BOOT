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
git clone https://github.com/hyppoliteaurelus/API-MEDVOLL-ALURA-SPRING-BOOT.git

## Banco de Dados

O projeto está configurado para usar o banco de dados H2 em memória para desenvolvimento e testes. O console do H2 pode ser acessado em `http://localhost:8080/h2-console` com as seguintes configurações:

- **JDBC URL:** `jdbc:h2:mem:testdb`
- **Username:** `sa`
- **Password:** (deixe em branco)
)
## Contribuição
1. Faça um fork do projeto.
2. Crie uma branch para sua feature (git checkout -b feature/sua-feature).
3. Commit suas mudanças (git commit -am 'Adicione sua feature').
4. Push para a branch (git push origin feature/sua-feature).
5. Crie um Pull Request.

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
