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

Durante o desenvolvimento do projeto, atuei principalmente na camada back-end e exerci o papel de Scrum Master, sendo responsável por coordenar as atividades da equipe e garantir a aplicação das metodologias ágeis utilizando o Jira para o acompanhamento das tarefas e sprints.
Contribuí ativamente para a modelagem inicial do banco de dados, padronização do código e implementação de soluções voltadas à eficiência, segurança e manutenção do sistema. Busquei constantemente melhorar a qualidade técnica do projeto, participando das decisões de arquitetura e promovendo boas práticas de desenvolvimento. Entre minhas entregas, destacam-se as refatorações pontuais, a definição e implementação de DTOs, a criação de endpoints personalizados para exportações em larga escala e o estabelecimento de padrões de código consistentes, garantindo a evolução sustentável e colaborativa do sistema.

<details>
  <summary>Modelagem inicial do banco de dados</summary>
<br>
Em conjunto com os demais membros do grupo, definimos a estrutura inicial do banco de dados, incluindo suas tabelas e relacionamentos. O foco foi criar um esquema que atendesse aos fluxos prioritários mapeados, com uma abordagem de visibilidade limitada a longo prazo. Para garantir a coerência e facilitar as alterações, elaboramos um dump do banco que é inicializado junto ao Docker, minimizando assim os conflitos decorrentes de futuras modificações em relacionamentos, tabelas ou na adição de novos componentes.

<br>

<img src="https://github.com/TiagoTReis/Portfolio-Projetos/blob/main/assets/3-semestre/modelagem%20.png?raw=true" width="100%"/>

</details>

<details>
  <summary>Desenvolvimento back-end utilizando SpringBoot</summary>

Contribuí com refatorações pontuais e implementação de DTOs para otimizar, padronizar e tornar o código mais manutenível. Atendi a solicitações do cliente criando endpoints para recuperação completa de dados, estabeleci padrões de código consistentes e priorizei eficiência, segurança e facilidade de evolução do sistema.

  <details>
    <summary>Estruturação de dados (DTO)</summary>

Defini e implementei DTOs (Data Transfer Objects) para padronizar a comunicação entre as camadas da aplicação. Com isso, garanti a transferência eficiente de dados, protegi entidades internas evitando exposições desnecessárias, e facilite a manutenção e evolução do sistema. Também otimizei a performance ao enviar apenas as informações necessárias, mantendo contratos claros entre front-end e back-end e permitindo alterações futuras na API sem impactos inesperados.

<br>

<img src="https://github.com/TiagoTReis/Portfolio-Projetos/blob/main/assets/3-semestre/refatoracao-de-dto.png?raw=true" width="100%"/>

  </details>

  <details>
    <summary>Padronização de Código</summary>

Estabeleci padrões de código consistentes para toda a equipe, garantindo legibilidade, uniformidade e manutenção eficiente do projeto. Essa iniciativa facilitou a colaboração entre desenvolvedores, reduziu a ocorrência de erros, aumentou a qualidade do código e promoveu boas práticas que facilitam a evolução e escalabilidade do sistema.

<br>

<img src="https://github.com/TiagoTReis/Portfolio-Projetos/blob/main/assets/3-semestre/refatoracao-de-dto.png?raw=true" width="100%"/>

  </details>

<details>
  <summary>Endpoint para exportações em Larga Escala </summary>
  
Atendi a uma solicitação do cliente durante um code review, criando endpoints que permitem a recuperação completa dos dados do banco, ignorando a paginação padrão. Essa implementação facilitou cenários de exportação de relatórios, análise de grandes volumes de informações e integrações com sistemas externos, garantindo eficiência e performance sem comprometer o funcionamento do sistema.

<br>

<img src="https://github.com/TiagoTReis/Portfolio-Projetos/blob/main/assets/3-semestre/endpoint.png?raw=true" width="100%"/>

</details>

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
