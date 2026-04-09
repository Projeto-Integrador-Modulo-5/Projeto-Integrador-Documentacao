# 📚 Projeto Integrador — Documentação Técnica (N1)

**Grupo:** Victor Hugo  
**Curso:** Análise e Desenvolvimento de Sistemas — 4º Período  
**Instituição:** PUC Goiás | **Semestre:** 2026/1

---

## 📁 Arquivos neste repositório

| Arquivo | Descrição |
|---|---|
| `DocumentacaoTecnica_N1.pdf` | Documento unificado com toda a documentação da N1 (38 páginas) |
| `ArquiteturaBackend.pdf` | Detalhamento da arquitetura de microsserviços e decisões técnicas |
| `ArquiteturaC4.pdf` | Diagramas C4 — Contexto e Container (modelo arquitetural) |
| `PlanoDeQualidadeTeste.pdf` | Plano de testes, métricas de aceitação e requisitos não-funcionais |

---

## 🔗 Repositórios do projeto

| Repositório | Descrição | Porta |
|---|---|---|
| [Projeto-Integrador-Infra](https://github.com/Projeto-Integrador-Modulo-5/Projeto-Integrador-Infra) | Docker Compose — orquestração de todos os serviços | — |
| [Projeto-Integrador-Backend](https://github.com/Projeto-Integrador-Modulo-5/Projeto-Integrador-Backend) | API REST principal (Spring Boot) | 8080 |
| [Projeto-Integrador-Logistics-Service](https://github.com/Projeto-Integrador-Modulo-5/Projeto-Integrador-Logistics-Service) | Serviço de processamento de pedidos | 8081 |
| [Projeto-Integrador-Notification-Service](https://github.com/Projeto-Integrador-Modulo-5/Projeto-Integrador-Notification-Service) | Notificações via WebSocket/SMTP | 8082 |
| [Projeto-Integrador-Frontend](https://github.com/Projeto-Integrador-Modulo-5/Projeto-Integrador-Frontend) | SPA React + Vite | 5173 |

---

## 🏗️ Visão geral da arquitetura

Plataforma de e-commerce de camisetas com arquitetura distribuída de microsserviços. A comunicação assíncrona entre serviços é feita via **Apache Kafka**, e o status dos pedidos é entregue ao cliente em tempo real via **WebSocket/STOMP**.

**Stack principal:** Java 21 · Spring Boot 3 · Apache Kafka · PostgreSQL · Redis · React 18 · Docker Compose

---

## ✅ Status da N1

- [x] Diagramas C4 (Contexto + Container)
- [x] Plano de Testes e requisitos não-funcionais
- [x] Ambiente Docker configurado
- [x] *Hello World* end-to-end validado (Kafka + WebSocket)
