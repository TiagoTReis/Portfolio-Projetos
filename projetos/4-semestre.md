<div align="center">

# 🚀 API 4º Semestre - 02/2025

<a href="https://github.com/DenariusData/API-4SEM" target="_blank">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositório GitHub">
</a>

### 🎓 Parceiro Acadêmico:
**FATEC São José dos Campos - Altave**

</div>

---

## 📌 Resumo do Projeto

Desenvolvimento de um **Sistema Inteligente de Monitoramento e Alerta de Tráfego** para a cidade de São José dos Campos. A plataforma transforma dados brutos de radares em insights estratégicos, permitindo a gestão de indicadores de tráfego e a alocação otimizada de agentes de mobilidade.

---

## ⚠️ Problema

A ausência de um sistema integrado que centralizasse os dados de radares urbanos. Não havia mecanismos automáticos para disparar alertas baseados em severidade ou ferramentas que facilitassem a designação de agentes para áreas críticas de congestionamento.

---

## 💡 Solução

Criamos uma solução que centraliza o controle de trânsito através de um monorepo. O sistema emite **alertas automáticos via Telegram**, possui um **dashboard interativo com mapas (Leaflet)** e permite o cadastro de níveis de severidade. A aplicação suporta 4 perfis de acesso, garantindo que desde o cidadão até o administrador tenham visões pertinentes aos seus cargos.

---

## 🛠 Tecnologias Adotadas

| Tecnologia | Descrição |
|:---:|:---|
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) <br> ![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) | Backend com Spring Security + JWT para controle de perfis, Spring Data JPA e Scheduler para monitoramento periódico. |
| ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) | Banco de dados relacional em nuvem (**Oracle Cloud DB**), acessado via Oracle Wallet para segurança máxima. |
| ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D) <br> ![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white) | Frontend SPA com Material Design, gerenciamento de estado via **Pinia** e integração com mapas interativos. |
| ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white) | Biblioteca de mapas para exibição de zonas e radares, utilizando **Turf.js** para operações geoespaciais. |
| ![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white) | Integração com Telegram Bot API para envio de alertas em tempo real aos agentes. |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Orquestração do ambiente com Docker Compose, garantindo volumes para Wallet e healthchecks. |

---

## 🧩 Metodologia

O projeto utilizou **Scrum** com foco em entregas incrementais e validação rigorosa via Jira:

- **Sprint 1:** Dashboards, mapas de zonas e CRUD de indicadores.
- **Sprint 2:** Sistema de alertas automáticos e associação de agentes a subzonas estratégicas.
- **Sprint 3:** Auditoria, sistema de permissões por perfil e visualização mobile para agentes.

---

## 👨‍💻 Contribuições Individuais

Atuei como **Developer Fullstack**, sendo responsável por funcionalidades críticas de ponta a ponta no sistema.

---

<details>
<summary><b>⚙️ Backend — Arquitetura de Dados e Sistema de Alertas</b></summary>

Liderei a estruturação do núcleo da aplicação no backend:
- **Modelagem JPA:** Mapeamento de 10+ entidades para o banco Oracle, garantindo integridade e tradução para o inglês.
- **Lógica de Alertas:** Implementação de filtros complexos com paginação e endpoints de "Top 5" alertas por região/critério.
- **Telegram Integration:** Desenvolvimento do serviço de disparos automáticos via Bot API, utilizando HTML parse mode e botões inline.
</details>

<details>
<summary><b>🎨 Frontend — Gestão de Usuários e Dashboards de Mapas</b></summary>

Fui responsável por módulos centrais da interface do usuário:
- **Módulo de Pessoas:** CRUD completo com modais dinâmicos, integração com Axios e paginação reutilizável.
- **Integração Leaflet:** Implementação de dashboards integrados ao mapa, permitindo que o gestor visualize alertas clicando em zonas da cidade.
- **Refatoração UI:** Unificação de componentes para reduzir duplicação de código.
</details>

<details>
<summary><b>🛠️ Hotfixes Críticos e Otimização</b></summary>

Atuei na resolução de problemas complexos de produção:
- **Recursão Infinita:** Correção de erros de StackOverflow causados por bidirecionalidade no JPA/Lombok.
- **Filtros de Perfil:** Implementação de camadas de segurança nos endpoints para garantir que agentes visualizem apenas dados de suas zonas atribuídas.
</details>

---

## 📚 Aprendizados Efetivos

Este semestre representou meu maior volume de contribuições técnicas. O uso do **Spring Security com JWT** foi um divisor de águas, ensinando como proteger rotas baseadas em perfis de acesso de forma profissional. 

Aprendi os perigos do uso excessivo de bibliotecas como Lombok em relacionamentos JPA, o que me tornou muito mais atento ao que acontece "por baixo do capô" no framework. A experiência com **Oracle Cloud DB** e o uso de **Oracle Wallet** trouxe o projeto para um nível de maturidade industrial, lidando com autenticação segura e infraestrutura em nuvem real.

---

## 🧠 Hard Skills

| Tecnologia/Metodologia | Nota | Classificação | O que me falta |
| :--- | :--- | :--- | :--- |
| **Metodologia Ágil Scrum** | ★★★★★ | Sei fazer com autonomia | Implementar métricas de qualidade técnica (Code Coverage) integradas ao Jira. |
| **Spring Security & JWT** | ★★★★☆ | Sei fazer com ajuda | Explorar autenticação OAuth2 com provedores externos (Google/GitHub). |
| **Oracle Cloud DB** | ★★★★☆ | Sei fazer com ajuda | Aprofundar em tunning de performance específico para arquitetura Oracle. |
| **Vue.js 3 & Pinia** | ★★★★☆ | Sei fazer com ajuda | Implementar testes unitários para componentes Vue utilizando Vitest. |
| **Leaflet & GeoJSON** | ★★★☆☆ | Entendi | Estudar manipulação avançada de polígonos complexos e geoprocessamento no backend. |

---

## 🤝 Soft Skills

| Soft Skill | Como desenvolvi neste projeto |
|:---|:---|
| **Proatividade Técnica** | Assumi a responsabilidade por entregas massivas (80+ commits), garantindo que tanto o front quanto o back evoluíssem em sincronia. |
| **Resolução de Problemas** | Diagnostiquei e corrigi bugs críticos de recursão e filtros de segurança sob pressão de entrega das Sprints finais. |
| **Adaptabilidade** | Transicionei com sucesso para uma nova equipe (Denarius Data) e dominei tecnologias novas em tempo recorde (Oracle Cloud, Leaflet). |
| **Visão Sistêmica** | Compreendi como a integração com APIs externas (Telegram) e bancos em nuvem impactam a arquitetura global e a segurança do software. |

---

## 🔎 Navegação entre Projetos

- [🚀 1º Semestre: Calculadora Científica](./1-semestre.md)
- [🧠 2º Semestre: Projeto Avaliador de Soft Skill](./2-semestre.md)
- [📊 3º Semestre: Sistema de Ponto e Geração de Relatórios](./3-semestre.md)
- [🛡️ 4º Semestre: Monitoramento e Resposta a Incidentes](./4-semestre.md)
- [📌 5º Semestre: TODO](./5-semestre.md)
- [📌 6º Semestre: TODO](./6-semestre.md)

---

<div align="center">

### ✨ Desenvolvido durante a graduação em Banco de Dados

</div>
