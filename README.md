<h1 align="center">Hanrry Santos</h1>

<h3 align="center">Desenvolvedor Backend Java | Spring Boot • Microsserviços • Mensageria</h3>

<p align="center"><i>Aberto a oportunidades como Desenvolvedor Backend Java.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/hanrrysantos"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="mailto:hanrry.jsantos@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;
  <a href="https://www.instagram.com/hanrrysantoss"><img src="https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

Estudante de Engenharia de Software na UEPA, com foco em sistemas backend que precisam manter consistência sob carga, concorrência e falha parcial.

Projetos pessoais focados em problemas reais de produção: consistência transacional em conciliação financeira, controle de vazão distribuído com Redis, e sincronização em lote de milhões de registros com Spring Batch.

Aplico arquitetura de microsserviços, comunicação assíncrona orientada a eventos (Kafka/RabbitMQ) e design de APIs REST resilientes com OpenFeign e circuit breakers.

Testes automatizados fazem parte do desenvolvimento, com cobertura medida por JaCoCo. Experiência prática levando esses sistemas a produção com AWS, Docker e pipelines de CI/CD.

---

### Tecnologias

<p align="left">
  <!-- Core Backend -->
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" height="30" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" height="30" alt="Spring Boot"/>

  <!-- Cloud, Infra & CI/CD -->
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" height="30" alt="AWS"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" height="30" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" height="30" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" height="30" alt="Linux"/>

  <!-- Bancos de Dados, Migrations & Caching -->
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" height="30" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" height="30" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" height="30" alt="Redis"/>

  <!-- Mensageria & Streaming -->
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" height="30" alt="RabbitMQ"/>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" height="30" alt="Kafka"/>

  <!-- Testes & Qualidade de Código -->
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" height="30" alt="JUnit 5"/>

  <!-- Observabilidade & Monitoramento -->
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" height="30" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" height="30" alt="Prometheus"/>

  <!-- Frontend -->
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" height="30" alt="TypeScript"/>

  <!-- Ferramentas -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" height="30" alt="Git"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" height="30" alt="Postman"/>
</p>

---

### Projetos em destaque

**E-commerce - Plataforma de Vendas** 🔗 [Repositório](https://github.com/hanrrysantos/e-commerce-microsservicos) · 🔗 [Swagger](https://ecommerce-api-gateway-to0z.onrender.com/swagger-ui.html)

Ecossistema escalável baseado em microsserviços e mensageria para fluxos de e-commerce distribuídos.
- **Destaques:** comunicação assíncrona orientada a eventos, resiliência de rede com OpenFeign, conteinerização e esteira de CI/CD completa.
- `Java` · `Spring Boot` · `RabbitMQ` · `Docker` · `GitHub Actions`

**Inventory Manager - Controle de Estoque Inteligente** 🔗 [Repositório](https://github.com/hanrrysantos/inventory-manager) · 🔗 [Swagger](https://inventory.hanrry.top/swagger-ui/index.html)

API REST de alta performance voltada para processamento em lote e sincronização massiva de dados.
- **Destaques:** sincronização automatizada via Spring Batch, evolução controlada de schema com Flyway, 98% de cobertura de testes monitorada via JaCoCo.
- `Java` · `Spring Batch` · `JUnit 5` · `Mockito` · `Flyway`

**ReconPay - Plataforma de Conciliação Financeira** 🔗 [Repositório](https://github.com/hanrrysantos/reconpay)

Sistema que simula cenários complexos de fintechs através da automação de conciliação de transações.
- **Destaques:** arquitetura de monólito modular com forte isolamento, auditoria e histórico via soft delete, segurança RBAC com JWT.
- `Java 21` · `Spring Boot 3` · `Spring Security & JWT` · `PostgreSQL` · `Flyway` · `Docker`

**Rate-Limiting Dinâmico** 🔗 [Repositório](https://github.com/hanrrysantos/rate-limiting)

Solução de segurança infraestrutural para proteção e controle de vazão de tráfego em microsserviços.
- **Destaques:** algoritmo Fixed Window distribuído em memória com Redis, validação dinâmica de API Keys com baixíssima latência.
- `Java` · `Spring Boot` · `Redis` · `PostgreSQL` · `Docker Compose`

**StudyTracker - Sistema de Gerenciamento de Estudos** 🔗 [Repositório](https://github.com/hanrrysantos/studytracker)

API focada no monitoramento hierárquico estruturado e gestão de progresso acadêmico.
- **Destaques:** consistência transacional e restrições de integridade no banco, autenticação stateless com JWT, infraestrutura pronta para produção na nuvem.
- `Java 21` · `Spring Boot 3` · `PostgreSQL` · `Supabase` · `Docker` · `Render`

**Controle de Gastos** 🔗 [Repositório](https://github.com/hanrrysantos/controle-de-gastos)

Aplicação web para gestão financeira, orçamento pessoal e consolidação de dados orçamentários.
- **Destaques:** dashboard analítico com agregação de dados financeiros em tempo real, isolamento de rotas via tokens JWT.
- `Java` · `Spring Boot` · `PostgreSQL` · `JWT Authentication`
