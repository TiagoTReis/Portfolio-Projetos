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


## 🛠️ Tecnologias Adotadas

| Tecnologia | Descrição |
| :---: | :--- |
| ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) | Linguagem principal utilizada para toda a lógica de negócio, controllers e modelos da aplicação (Requisito funcional do cliente). |
| ![JavaFX](https://img.shields.io/badge/JavaFX-blue?style=for-the-badge&logo=java&logoColor=white) ![FXML](https://img.shields.io/badge/FXML-gray?style=for-the-badge) | Framework para construção da interface gráfica desktop, utilizando o padrão declarativo para separação entre layout e lógica. |
| ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) | Banco de dados relacional utilizado para a persistência de dados de alunos, equipes, sprints e avaliações. |
| ![JDBC](https://img.shields.io/badge/JDBC-red?style=for-the-badge&logo=java&logoColor=white) | Driver de conexão para execução de queries e operações CRUD diretamente no banco de dados, sem o uso de ORMs. |
| ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) | Gestão de versionamento com estratégia de branches por feature e revisão rigorosa via Pull Requests. |
---

## 🧩 Metodologia

O projeto utilizou o framework **Scrum** dividido em 4 Sprints:

- **Sprint 1:** Prototipação, validação de wireframes e definição da arquitetura.
- **Sprint 2:** Core do sistema — Avaliação entre alunos e importação de dados via CSV.
- **Sprint 3:** Dashboard do professor, geração de relatórios e gestão de critérios.
- **Sprint 4:** Sistema de login, controle de períodos de avaliação e pontuação máxima.

---

## 👤 Contribuições Individuais

Atuei com um papel híbrido e estratégico como **Scrum Master** e **Desenvolvedor Full-Stack**, sendo responsável pela governança do projeto e pela implementação de fluxos críticos de interface e lógica de negócio. Minha atuação garantiu a transição entre o planejamento ágil e a entrega técnica de funcionalidades essenciais para o controle de avaliações.

<details>
  <summary>🗄️ Modelagem e Gestão do Banco de Dados (MySQL)</summary>
  <br>
  Participei ativamente da concepção estrutural do projeto, garantindo que a base de dados fosse capaz de suportar as regras de negócio complexas de uma aplicação de gestão acadêmica.
  <br><br>
  As principais contribuições foram:
  <br><br>
  <ul>
    <li>
      <b>Diagrama Entidade-Relacionamento (DER):</b> Auxiliei no processo de criação e refinamento do DER, assegurando a integridade referencial e a normalização dos dados entre as entidades de alunos, grupos, sprints e critérios de avaliação.
      <br><br>
      <details>
        <summary><i>Clique para ver a imagem</i></summary>
        <br>
        <img src="https://raw.githubusercontent.com/TiagoTReis/Portfolio-Projetos/main/assets/2-semestre/merAtualizado.jpeg" alt="Diagrama Entidade Relacionamento" width="100%">
      </details>
      <br>
    </li>
   </ul>
</details>

<details>
  <summary><strong>💻 Desenvolvimento Front-end (JavaFX)</strong></summary>
  <br>

  No front-end, fui responsável pela construção das interfaces e fluxos principais da aplicação, garantindo usabilidade e interação eficiente para alunos e professores.
  <br><br>

  <details>
    <summary>🏠 Tela Principal (Home)</summary>
    <br>
    
- Implementação da navegação base da aplicação (`HomeControlScreen.java` + `principalScreen.fxml`)
- Organização do fluxo entre as funcionalidades principais

  </details>

  <br>

  <details>
    <summary>📝 Telas de Configuração (Professor)</summary>
    <br>

**Definição de Pontuação**
- Criação da interface (`SetScore.fxml`)
- Implementação de botões e interações

<br>

**Definição de Datas de Sprint**
- Desenvolvimento da tela (`SetSprintData.fxml`)

  </details>

  <br>

  <details>
    <summary>🎯 Tela de Avaliação</summary>
    <br>

- Interface para avaliação entre alunos  
- Integração com ações de envio (botão enviar)

  </details>

  <br>

  <details>
    <summary>🎨 Ajustes de Interface</summary>
    <br>

- Adição e organização de botões  
- Melhorias de layout e usabilidade  

  </details>

</details>

<br>

<details>
  <summary><strong>⚙️ Lógica de Negócio e Back-end (Java)</strong></summary>
  <br>

  Atuei na implementação das regras responsáveis pelo processamento das avaliações.
  <br><br>

  <details>
    <summary>🧠 Motor de Avaliação</summary>
    <br>

- Desenvolvimento da lógica no `StudentEvaluator.java`  
- Processamento e envio das avaliações  
- Garantia de consistência dos dados  

  </details>

  <br>

  <details>
    <summary>📊 Regras de Pontuação</summary>
    <br>

- Implementação de limite máximo de pontuação  
- Aplicação de validações  

  </details>

  <br>

  <details>
    <summary>🔄 Integração Front-end ↔ Back-end</summary>
    <br>

- Criação de métodos para ações da interface  
- Conexão entre telas e regras de negócio  

  </details>

</details>

<br>

<details>
  <summary><strong>🛠️ Refatoração e Arquitetura</strong></summary>
  <br>

  Foco na melhoria da qualidade, organização e manutenibilidade do código.
  <br><br>

  <details>
    <summary>🔧 Padronização de Modelos</summary>
    <br>

- Refatoração do `SprintModel.java`  
- Remoção de atributos estáticos  
- Padronização de nomenclatura (inglês)  

  </details>

  <br>

  <details>
    <summary>⚡ Interface Reativa (JavaFX)</summary>
    <br>

- Uso de JavaFX Properties  
- Implementação de Data Binding  

  </details>

  <br>

  <details>
    <summary>🧹 Limpeza de Código</summary>
    <br>

- Remoção de comentários desnecessários  
- Organização geral do código  

  </details>

</details>

<br>

<details>
  <summary><strong>📚 Documentação</strong></summary>
  <br>

- Atualização do README  
- Criação de materiais de apoio  
  - Manual do usuário  
  - GIFs demonstrando funcionalidades  
  - MER atualizado  

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
