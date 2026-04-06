##Controle-de-Acesso-a-Condominios##


|05/06/2026| Criação da entidade User
|05/06/2026| Criar estrutura inicial do projeto Spring Boot
- Foi criada a estrutura padrão para o projeto, separação de pacotes
- Feita a configuração do banco

## Como rodar localmente
- git clone https://github.com/Robson-Franco/Sistema-de-Controle-de-Acesso-a-Condominios.git
- Configure as informações do seu banco no applications.properties

## Tecnologias utilizadas
- Java (recomendado: 17+)
- Spring Boot
- Spring Data JPA
- Spring Security
- Maven
- H2 Database ou PostgreSQL (opcional)


## Estrutura do Projeto

- src/
  - main/
    - java/
      - br/com/seuprojeto/acesso/
        - controller/
        - service/
        - repository/
        - domain/
        - dto/
        - config/
    - resources/
      - application.properties