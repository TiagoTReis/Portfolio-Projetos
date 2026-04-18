<div align="center">

# 🚀 API 3º Semestre - 01/2025

<a href="https://github.com/SQLutions-FATEC/API-3-Semestre" target="_blank">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositório GitHub">
</a>

### 🎓 Parceiro Acadêmico:
**FATEC São José dos Campos - Altave**

</div>

---

## 📌 Resumo do Projeto

Desenvolvimento de um **Sistema de Controle de Ponto**, focado no monitoramento de movimentações de funcionários. A aplicação permite o registro de horários, cálculo automático de horas trabalhadas e visualização de dados através de dashboards interativos e relatórios gerenciais.

---

## ⚠️ Problema

A empresa parceira (**Altave**) necessitava de uma solução eficiente para monitorar possíveis atrasos de funcionários terceirizados. A falta de um sistema centralizado gerava impactos operacionais e dificultava a análise de produtividade das prestadoras de serviço.

---

## 💡 Solução

Criamos uma aplicação web integrada a um banco de dados externo para exibir informações de entrada e saída em tempo real. O sistema conta com filtros avançados, visualização gráfica e geração de relatórios personalizados, facilitando a tomada de decisão estratégica pela gestão.

---

## 🛠 Tecnologias Adotadas

| Tecnologia | Descrição |
|:---:|:---|
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) | Utilizados no desenvolvimento do backend para construção de uma API RESTful robusta e escalável. |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) | Banco de dados relacional principal, com foco em tabelas normalizadas, triggers de integridade e índices de performance. |
| ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D) | Framework JavaScript utilizado no frontend para criar interfaces dinâmicas e dashboards interativos. |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Empregados para containerizar a aplicação (API, Banco e Crawler), garantindo a paridade entre os ambientes. |
| ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white) | Gerenciamento de dependências e automação de build para integração de bibliotecas como Jsoup e Spring Data. |

---

## 🧩 Metodologia

O projeto foi gerido via **Jira**, utilizando o framework Scrum para organizar as entregas:

- **Gestão de Backlog:** Mapeamento de User Stories focadas nos fluxos de controle de ponto.
- **Monitoramento Ágil:** Uso de gráficos de *Burndown* para acompanhar o progresso das Sprints.
- **Sessões de Peer Programming:** Implementadas para destravar bloqueios técnicos e acelerar o aprendizado do time.

---

## 👨‍💻 Contribuições Individuais

Atuei como **Scrum Master** e **Developer Backend**, focando na arquitetura de dados e padronização do sistema.

---

<details>
<summary><b>🗄️ Modelagem de Dados e Infraestrutura Docker</b></summary>

Liderei a definição da estrutura inicial do banco de dados e a orquestração do ambiente:
- Elaboração do esquema de tabelas e relacionamentos para suportar os fluxos prioritários.
- Criação de scripts SQL (dump) para inicialização automática do banco via Docker, evitando conflitos entre desenvolvedores.
</details>

<details>
<summary><b>⚙️ Desenvolvimento Backend e Padronização de Código</b></summary>

Implementei soluções voltadas à manutenibilidade e eficiência do sistema:
- **Implementação de DTOs:** Garanti a segurança e performance ao trafegar apenas os dados necessários entre as camadas.
- **Padronização de Código:** Estabeleci diretrizes de nomenclatura e arquitetura, reduzindo erros e facilitando a colaboração.
- **Endpoints de Exportação:** Desenvolvi endpoints personalizados para recuperação de dados em larga escala, atendendo requisitos de relatórios complexos.
</details>

<details>
<summary><b>📋 Scrum Master — Facilitação e Gestão</b></summary>

Responsável por manter a cadência e a saúde do projeto:
- Facilitação de Daily Meetings, Reviews e Retrospectives.
- Gestão de impedimentos junto aos Stakeholders (Altave) e professores da FATEC.
- Monitoramento da qualidade das entregas através de revisões no GitHub e acompanhamento no Jira.
</details>

---

## 📚 Aprendizados Efetivos

Este semestre consolidou meus conhecimentos em **arquitetura de sistemas distribuídos**. O uso do **Docker** foi fundamental para entender como garantir que a aplicação funcione da mesma forma em qualquer máquina. 

No desenvolvimento com **Java/Spring Boot**, evoluí na aplicação de padrões como DTO e princípios **SOLID**, percebendo que a padronização do código é a chave para um projeto escalável. Como **Scrum Master**, aprendi a importância da liderança situacional: identificar gargalos técnicos precocemente e propor sessões de programação em par foi o que garantiu o cumprimento dos prazos acadêmicos e técnicos.

---

## 🧠 Hard Skills

| Tecnologia/Metodologia | Nota | Classificação | O que me falta |
| :--- | :--- | :--- | :--- |
| **Metodologia Ágil Scrum** | ★★★★★ | Sei fazer com autonomia |  |
| **Java & Spring Boot** | ★★★☆☆| Entendi | Explorar técnicas de cache e otimização de queries complexas para grandes volumes de dados. |
| **PostgreSQL** | ★★★★☆ | Sei fazer com ajuda | Estudar procedimentos armazenados complexos e otimização de planos de execução. |
| **Docker** | ★★★☆☆ | Entendi | Praticar a criação de imagens otimizadas (multi-stage builds) e persistência de volumes complexos. |
| **Vue.js** | ★★★☆☆ | Entendi | Dominar o gerenciamento de estado global (Pinia/Vuex) para aplicações maiores. |

---

## 🤝 Soft Skills

| Soft Skill | Como desenvolvi neste projeto |
|:---|:---|
| **Gestão de Tempo** | Como Scrum Master, gerenciei as metas semanais via Jira e burndown charts para garantir as entregas no prazo. |
| **Empatia e Mentoria** | Propus sessões de *peer programming* para ajudar colegas com dificuldades técnicas, fortalecendo a união do time. |
| **Alinhamento com Stakeholders** | Atuei como interface técnica para destravar requisitos junto aos professores quando o feedback do cliente externo oscilava. |
| **Resiliência e Colaboração** | Mantive o ambiente produtivo e focado em soluções coletivas, transformando divergências técnicas em aprendizado para o grupo. |

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
