```markdown
# NLW Connect Java 🚀

## 📌 Sobre o Projeto

Nessa trilha, explorei conceitos fundamentais do ecossistema **Java** e **Spring Boot**, mergulhando na prática para construir uma aplicação completa de **inscrição em eventos**.  

Ao longo do curso, configurei o ambiente de desenvolvimento, utilizamos o **Spring Initializr** para criar nosso projeto e conectamos a aplicação a um banco de dados **MySQL**.  

## 🛠️ Tecnologias Utilizadas

- Java 17 
- Spring Boot  
- Spring Data JPA
- MySQL 
- Maven  
- Lombok
- Docker (para rodar o banco de dados)  
- Postman (para testes das APIs)  
- MySQL Workbench (para gerenciar o banco de dados)   

## 📋 Funcionalidades Implementadas

✔️ Cadastro e recuperação de eventos por ID e URL
✔️ Modelagem de entidades para inscrição de usuários  
✔️ Validação de regras de negócio  
✔️ Geração de relatórios, incluindo:  
   - Número total de inscritos  
   - Inscrições por indicação  
   - Ranking de usuários  


## 📂 Estrutura do Projeto


NLW-Connect-Java
│── src/main/java/br/com/nlw/events
│   ├── controller        # Controllers da API
│   ├── dto               # Data Transfer Objects (DTOs)
│   ├── exception         # Classes para tratamento de exceções
│   ├── model             # Entidades do banco de dados
│   ├── repository        # Repositórios (Spring Data JPA)
│   ├── service           # Regras de negócio
│── src/main/resources
│   ├── application.properties  # Configuração do banco de dados
│── pom.xml               # Gerenciamento de dependências (Maven)
└── README.md             # Documentação do projeto



🚀 Projeto desenvolvido durante a NLW Connect by [@layssahillary].  
