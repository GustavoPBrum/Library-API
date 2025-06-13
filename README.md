# Spring Data JPA

## Introdução
O módulo **Spring Data JPA** é para integrar persistência de dados com uma aplicação Spring Boot. Ele simplifica as interações com bancos de dados relacionais, utilizando abstrações poderosas como repositórios e mapeamentos de entidades.

---

## Conteúdo do Módulo

### 1. Configuração do Projeto
- Configuração inicial do projeto com as dependências necessárias, incluindo o Spring Data JPA e o driver JDBC apropriado para o banco de dados.
- Definição das propriedades essenciais no arquivo de configuração, como URL do banco de dados, usuário, senha, e estratégia de geração de schema.

---

### 2. Mapeamento de Entidades
- Introdução ao conceito de entidades no JPA.
- Explicação das principais anotações utilizadas, como `@Entity`, `@Table`, `@Id` e `@GeneratedValue`.
- Discussão sobre a importância de definir atributos como chaves primárias e configurar colunas do banco de dados corretamente.

---

### 3. Repositórios
- Apresentação das interfaces disponíveis para trabalhar com repositórios no Spring Data JPA, como `CrudRepository`, `JpaRepository` e `PagingAndSortingRepository`.
- Explicação sobre como criar métodos personalizados baseados nos nomes dos métodos e no uso de consultas derivadas.

---

### 4. Relacionamentos
- Discussão sobre os tipos de relacionamentos entre entidades: `One-to-One`, `One-to-Many`, `Many-to-One` e `Many-to-Many`.
- Explicação sobre estratégias de carregamento de dados (fetch types), incluindo `EAGER` e `LAZY`, e como elas impactam o desempenho da aplicação.

---

### 5. Consultas Personalizadas
- Introdução ao uso de consultas personalizadas com JPQL e SQL nativo.
- Explicação sobre como utilizar anotações como `@Query` para criar consultas específicas e otimizadas.
- Abordagem sobre como definir parâmetros e retornar projeções específicas.

---

### 6. Paginação e Ordenação
- Apresentação dos conceitos de paginação e ordenação no Spring Data JPA.
- Discussão sobre como utilizar `Pageable` e `Sort` para otimizar consultas que retornam grandes volumes de dados.

---

### 7. Testes com Banco H2
- Introdução ao uso do banco de dados H2 em memória para testes.
- Configuração do ambiente de teste e definição de propriedades específicas para executar cenários controlados.
- Benefícios do uso de bancos em memória durante o desenvolvimento e a automação de testes.

---

## Recursos Adicionais
- [Documentação Oficial Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [Guia de JPQL e Hibernate](https://docs.jboss.org/hibernate/orm/current/userguide/html_single/Hibernate_User_Guide.html)

---

### Sobre o Desenvolvedor

Este projeto foi desenvolvido por [Gustavo Pereira Brum](https://www.linkedin.com/in/gustavo-pereira-brum-42671b241/), estudante de Engenharia de Software, entusiasta de Java e apaixonado por desenvolvimento backend.
Em conjunto com os conteudos aprendidos no [SpringBoot Expert](https://www.udemy.com/course/spring-boot-expert/?couponCode=24T2MT120625A) do professor Dougllas Sousa.  