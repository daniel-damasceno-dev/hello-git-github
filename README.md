# Sistema de Gerenciamento de Tarefas

## Descrição
Este é um sistema de gerenciamento de tarefas desenvolvido em Java com Spring Boot.

## Funcionalidades
- Criação de tarefas
- Edição de tarefas
- Exclusão de tarefas
- Listagem de tarefas
- **NOVO: Filtro por prioridade (adicionado por você)**
- **NOVO: Busca por palavras-chave (adicionado por você)**

## Tecnologias Utilizadas
- Java 17
- Spring Boot 3.2
- PostgreSQL
- Maven
- JUnit 5

## Como Executar
```bash
mvn clean install
mvn spring-boot:run
```

## Configuração do Banco de Dados
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/taskdb
spring.datasource.username=admin
spring.datasource.password=senha123
```

## Testes
Para rodar os testes:
```bash
mvn test
```

## Autor
Seu Nome - Desenvolvedor Backend

## Licença
MIT License
