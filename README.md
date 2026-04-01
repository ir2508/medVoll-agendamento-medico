# 🏥 Med.Voll API

[![Java Version](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)](https://www.oracle.com/java/technologies/downloads/#java17)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5.13-brightgreen?style=for-the-badge&logo=springboot)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-Build-blue?style=for-the-badge&logo=apache-maven)](https://maven.apache.org/)

## 📝 Visão Geral
A **Med.Voll API** é uma solução robusta desenvolvida para a gestão hospitalar moderna. 

## 🚀 Stack Tecnológica e Decisões Arquiteturais

* **Java 17 (LTS):** Utilização de recursos modernos como *Sealed Classes*, *Records* e melhorias de performance na JVM.
* **Spring Boot 3.5.13:** Base da aplicação, aproveitando o ecossistema para autoconfiguração e produtividade.
* **Spring Web (MVC):** Implementação de arquitetura RESTful com foco em desacoplamento e semântica HTTP.
* **Lombok:** Padronização de código e redução de verbosidade, mantendo o foco na lógica de negócio.
* **Spring DevTools:** Otimização do fluxo de desenvolvimento (Hot Reload).

## 🏗️ Estrutura de Projeto

```text
src/main/java/med/voll/api
├── domain/            # Core da aplicação: Entidades JPA e Regras de Negócio
├── controller/        # Interface de entrada (REST Controllers)
├── repository/        # Abstração de persistência (Spring Data JPA)
├── service/           # Orquestração de regras complexas e transações
├── infra/             # Configurações transversais (Segurança, Exception Handlers)
└── dto/               # Objetos de transferência de dados (Records)
