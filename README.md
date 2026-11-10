# OmniOrder 🚀

Backend corporativo desenvolvido em **Java 21** e **Spring Boot** com arquitetura em camadas, construído como parte de um roadmap prático para consolidação de conhecimentos em engenharia de software backend, mensageria e DevOps.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Linguagem:** Java 21
* **Framework:** Spring Boot 3.x
  * Spring Web
  * Spring Data JPA
  * Spring Boot Validation
* **Banco de Dados:** PostgreSQL
* **Utilitários:** Lombok
* **Gerenciador de Dependências:** Maven

---

## 🏗️ Arquitetura do Projeto (Modelo em Camadas)

O projeto segue a tradicional arquitetura em camadas para clara separação de responsabilidades:

```text
src/main/java/br/com/omni/omniorder/
├── controller/     # Portas de entrada HTTP (Endpoints REST)
├── service/        # Regras de negócio da aplicação
├── repository/     # Interfaces de persistência (Spring Data JPA)
├── model/          # Entidades mapeadas para o banco de dados (JPA Entities)
└── dto/            # Objetos de Transferência de Dados (Data Transfer Objects)
