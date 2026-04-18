<div align="center">

# 🚀 API 2º Semestre - 02/2024

<a href="https://github.com/SQLutions-FATEC/API-2-Semestre" target="_blank">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositório GitHub">
</a>

### 🎓 Parceiro Acadêmico:
**FATEC São José dos Campos - Prof. Jessen Vidal**

</div>


## 📌 Resumo do Projeto

Desenvolvimento de um **Sistema Avaliador de Soft Skills** baseado na metodologia **PACER** (Proatividade, Autonomia, Colaboração e Entrega de Resultados).

A solução resolve o problema de processamento manual de avaliações enfrentado pelos professores, automatizando o cálculo de médias e a gestão de equipes através de uma aplicação desktop robusta.

---

## ⚠️ Problema

Os professores recebiam avaliações PACER em formatos heterogêneos e sem padronização. A ausência de cálculo automático de médias por sprint gerava um consumo excessivo de tempo administrativo e dificultava o acompanhamento do desempenho dos alunos.

---

## 💡 Solução

Foi desenvolvida uma aplicação desktop em **Java** com **JavaFX**, permitindo que alunos realizem avaliações padronizadas entre membros da equipe. O sistema calcula automaticamente as médias das Sprints e oferece ao professor um painel de controle para gerenciar critérios, prazos e exportar relatórios em formato CSV.

---


## 🛠 Tecnologias Adotadas

| Tecnologia | Descrição |
|:---|:---|
| **Java** | Linguagem principal utilizada para toda a lógica de negócio, controllers e modelos da aplicação (Requisito funcional do cliente). |
| **JavaFX + FXML** | Framework para construção da interface gráfica desktop, utilizando o padrão declarativo para separação entre layout e lógica. |
| **MySQL** | Banco de dados relacional utilizado para a persistência de dados de alunos, equipes, sprints e avaliações. |
| **JDBC** | Driver de conexão para execução de queries e operações CRUD diretamente no banco de dados, sem o uso de ORMs. |
| **Git & GitHub** | Gestão de versionamento com estratégia de branches por feature e revisão rigorosa via Pull Requests. |

---

## 🧩 Metodologia

O projeto utilizou o framework **Scrum** dividido em 4 Sprints:

- **Sprint 1:** Prototipação, validação de wireframes e definição da arquitetura.
- **Sprint 2:** Core do sistema — Avaliação entre alunos e importação de dados via CSV.
- **Sprint 3:** Dashboard do professor, geração de relatórios e gestão de critérios.
- **Sprint 4:** Sistema de login, controle de períodos de avaliação e pontuação máxima.

---

## 👨‍💻 Contribuições Individuais

Atuei com duplo papel: **Scrum Master** (facilitação e gestão) e **Developer** (interfaces e modelos).

---

<details>
<summary><b>🔧 Desenvolvimento Front-end e Lógica de Avaliação</b></summary>

Fui responsável pela construção do fluxo principal do sistema, garantindo a usabilidade para o aluno:
- Implementação do controller `HomeControlScreen.java` e integração com `principalScreen.fxml`.
- Desenvolvimento da lógica de envio de avaliações no `StudentEvaluator.java`.
- Criação de interfaces administrativas como `SetScore.fxml` e `SetSprintData.fxml` para controle do professor.
</details>

<details>
<summary><b>🛠 Refatoração e Arquitetura de Modelos</b></summary>

Trabalhei na melhoria da integridade do código e padronização:
- Refatoração completa do `SprintModel.java`, removendo atributos estáticos e padronizando variáveis para o inglês.
- Implementação de **JavaFX Properties** para permitir binding reativo na interface.
- Limpeza de código legado para garantir a manutenção do sistema.
</details>

<details>
<summary><b>📋 Scrum Master — Gestão e Documentação</b></summary>

Como facilitador da equipe, assegurei a qualidade das entregas:
- Revisão e merge de mais de 10 **Pull Requests**.
- Documentação do README com relatórios de Sprint, **Burndown Charts** e manuais em PDF.
- Criação de artefatos visuais (GIFs demonstrativos e MER atualizado) para facilitar a compreensão do projeto.
</details>

---

## 📚 Aprendizados Efetivos

Este semestre marcou um salto de complexidade técnica com a introdução do ecossistema Java.

Aprendi a importância da **Separação de Responsabilidades** através do padrão MVC, entendendo como o JavaFX separa a interface (FXML) da lógica (Controller). A refatoração de modelos me ensinou que a consistência na nomenclatura e o uso de tipos reativos (**JavaFX Properties**) são cruciais para sistemas escaláveis.

No papel de **Scrum Master**, desenvolvi uma visão sistêmica do projeto, aprendendo que a gestão de branches e a revisão de código são tão importantes quanto a escrita do código em si. A documentação deixou de ser uma tarefa secundária e passou a ser vista como parte integrante do produto final.

---

## 🧠 Hard Skills

| Tecnologia/Metodologia | Nota | Classificação | O que me falta |
| :--- | :--- | :--- | :--- |
| **Metodologia Ágil Scrum** | ★★★★★ | Sei fazer com autonomia |  |
| **Java** | ★★★☆☆ | Entendi | Explorar conceitos avançados como Streams API e Concorrência. |
| **JavaFX** | ★★★★☆ | Sei fazer com ajuda | Aprofundar em customização de CSS e componentes complexos de UI. |
| **MySQL / JDBC** | ★★★☆☆ | Entendi | Estudar otimização de queries e transações complexas via código. |
| **Git & GitHub** | ★★★★★ | Sei fazer com autonomia |  |

---

## 🤝 Soft Skills

| Soft Skill | Como desenvolvi neste projeto |
|:---|:---|
| **Liderança Servidora** | Como Scrum Master, atuei removendo impedimentos da equipe e garantindo o foco nas entregas. |
| **Gestão de Tempo** | Conciliei as responsabilidades de desenvolvimento técnico com as tarefas de gestão e documentação. |
| **Alinhamento com Stakeholders** | Apoiei o PO na facilitação de reuniões de validação de wireframes com os professores, garantindo que os requisitos técnicos estivessem claros para o time. |
| **Visão Analítica** | Analisei o código de outros membros durante os Pull Requests para garantir a qualidade do repositório. |

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
