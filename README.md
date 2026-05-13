<h1 align="center">Augusto Farcic</h1>

<p align="center">
  Desenvolvedor Backend Java em formação, com foco em APIs REST, Spring Boot, segurança, bancos relacionais e boas práticas de construção de software.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/augusto-farcic-a8a4b4368">LinkedIn</a>
  ·
  <a href="mailto:augustofarcic@gmail.com">augustofarcic@gmail.com</a>
  ·
  <a href="https://github.com/Farcicdev">GitHub</a>
</p>

---

## Sobre mim

Sou desenvolvedor backend buscando oportunidade como **Desenvolvedor Java Júnior**. Tenho praticado desenvolvimento de APIs com separação em camadas, autenticação, autorização, validação de dados, persistência com JPA, migrations de banco e documentação de endpoints.

Meu foco atual é construir projetos que se aproximem de problemas reais de backend: cadastro e gestão de usuários, controle de acesso, integração com APIs externas, tratamento padronizado de erros e ambiente local reproduzível com Docker.

## Stack principal

<p>
  <img src="https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17" />
  <img src="https://img.shields.io/badge/Spring_Boot-4.0-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

**Backend:** Java, Spring Boot, Spring Web MVC, Spring Data JPA, Spring Security, JWT, BCrypt<br>
**Banco de dados:** PostgreSQL, Flyway, Hibernate<br>
**Integrações e documentação:** OpenFeign, ViaCEP, Swagger/OpenAPI, DTOs, Bean Validation<br>
**Ferramentas:** Maven, Docker Compose, Git, IntelliJ IDEA, Linux

## Projetos em destaque

### [UsersApp](https://github.com/Farcicdev/UsersApp)

API REST para cadastro, autenticação e gerenciamento de usuários, com foco em segurança, regras de acesso e integração externa.

**Principais recursos:**

- Autenticação stateless com JWT Bearer.
- Senhas protegidas com BCrypt.
- Controle de acesso com roles `USER` e `ADMIN`.
- Autorização por dono do recurso: usuário comum só altera, troca senha ou exclui a própria conta.
- Invalidação de tokens antigos após alteração de senha.
- CRUD de usuários com paginação e ordenação.
- Integração com ViaCEP usando OpenFeign para preenchimento de endereço por CEP.
- Documentação interativa com Swagger/OpenAPI.
- PostgreSQL com Flyway para versionamento do banco.
- Ambiente local com Docker Compose.

**Tecnologias:** Java 17, Spring Boot 4, Spring Security, JWT, Spring Data JPA, PostgreSQL, Flyway, OpenFeign, Swagger/OpenAPI, Docker Compose, Maven.

### [FootApi](https://github.com/Farcicdev/FootApi)

API REST para gerenciamento de clubes, jogadores, estádios e usuários em um domínio de futebol brasileiro.

**Principais recursos:**

- CRUD e consultas paginadas para recursos do domínio.
- Autenticação com JWT assinado por chaves RSA.
- Autorização por escopos, como `club:read`, `club:write`, `player:read`, `player:write` e `admin:all`.
- Proteção de endpoints com Spring Security e method security.
- Entidades JPA, DTOs e mapeamento com MapStruct.
- Validação de entrada com Jakarta Validation.
- Tratamento centralizado de exceções.
- PostgreSQL com migrations Flyway e carga inicial de clubes/estádios.
- Testes automatizados em service e mapper.
- Ambiente local com Docker Compose.

**Tecnologias:** Java 17, Spring Boot 4, Spring Security, OAuth2 Resource Server, JWT RSA, Spring Data JPA, PostgreSQL, Flyway, MapStruct, Lombok, Docker Compose, Maven, JUnit.

## O que estes projetos demonstram

- Capacidade de construir APIs REST organizadas em controller, service, repository, entity, DTO e mapper.
- Conhecimento prático de autenticação, autorização, roles, escopos e proteção de rotas.
- Uso de banco relacional com modelagem, relacionamentos JPA e migrations versionadas.
- Integração com serviços externos usando cliente HTTP declarativo.
- Preocupação com validação, tratamento de erros e respostas consistentes.
- Entendimento de ambiente local reproduzível com Docker Compose.
- Evolução constante em testes, documentação e boas práticas de backend.

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Farcicdev&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Farcicdev&layout=compact&theme=github_dark&hide_border=true" alt="Top languages" />
</p>

---

<p align="center">
  Aberto a oportunidades como Desenvolvedor Backend Java Júnior.
</p>
