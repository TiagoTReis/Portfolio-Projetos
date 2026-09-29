<div align="center">
  
# API 5º Semestre - 01/2026 <br>

<a href="https://github.com/23deFevereiro" target="_blank"> <img src="https://img.shields.io/badge/Repositório-555555?style=for-the-badge&logo=github&logoColor=white"> </a><br>
### Parceiro Acadêmico:

FATEC São José dos Campos - Prof. Jessen Vidal

### Empresa Parceira:

SIATT - Sistemas Integrados de Alto Teor Tecnológico

</div>

---

## Resumo do Projeto

Desenvolvimento da plataforma analítica **Lunae** para a SIATT – Sistemas Integrados de Alto Teor Tecnológico. A solução integra dados dispersos de projetos, programas, compras, tarefas e horas trabalhadas, consolidando informações atualmente fragmentadas em diferentes sistemas e tabelas. Por meio da importação de arquivos CSV, os dados são processados, tratados e armazenados em uma base estruturada, permitindo consultas analíticas precisas. Complementado por um dashboard interativo com gráficos de barras e linhas, a ferramenta oferece visão consolidada e multidimensional do consumo de recursos, evolução de custos e esforço técnico por projeto e programa, apoiando a gestão estratégica e a tomada de decisão.

---

## Problema

A SIATT não possuía uma visão integrada das informações relacionadas a pedidos de compras, ordens, compromissos de materiais, controle de estoque, tarefas de desenvolvimento e horas trabalhadas, que estavam distribuídas em diferentes tabelas e sistemas. A ausência de integração dificultava a análise do custo real dos projetos, a comparação entre programas institucionais e o acompanhamento do consumo de materiais e horas técnicas ao longo do tempo. Gestores e responsáveis pelo acompanhamento financeiro enfrentavam dificuldades para responder perguntas essenciais, como o custo total por projeto em materiais, o valor despendido em horas técnicas e o custo real do produto considerando materiais e esforço de desenvolvimento.

---

## Solução

Implementação de uma plataforma analítica completa que integra dados das áreas de projetos, compras e desenvolvimento, estruturados para apoiar análises históricas e estratégicas. A solução permite a importação de arquivos CSV fornecidos pela parceira, com processamento e tratamento dos dados para armazenamento em banco de dados estruturado. O sistema disponibiliza um **dashboard interativo** com gráficos de barras e linhas, permitindo que gestores acompanhem o consumo de recursos, a evolução dos custos e o esforço técnico por projeto e programa, além de aplicar filtros para explorar diferentes cenários. Construído de forma colaborativa com a equipe da SIATT por meio de interações via Slack, seguindo metodologia ágil incremental, o Lunae oferece uma visão multidimensional que viabiliza a geração de indicadores relevantes para a gestão de programas e projetos estratégicos da empresa.

---

## Tecnologias Adotadas

| Tecnologia | Descrição |
|:---:|:---|
| ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D) | Framework web utilizado para construir o frontend interativo, com dashboards dinâmicos. |
| ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) | Framework web em Python utilizado no backend para a API RESTful, com arquitetura MVT e ORM integrado, responsável pelo processamento dos dados importados via CSV, tratamento e armazenamento no banco. |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) | Banco de dados relacional utilizado para armazenar os dados de programas, projetos e tarefas. |
| ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) | Ferramenta de design utilizada para prototipação e validação de interface com o cliente. |
| ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) <br> ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) | Controle de versionamento distribuído e hospedagem de repositórios, com gestão de issues, pull requests, revisões de código e integração contínua. |
| ![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=for-the-badge&logo=sonarcloud&logoColor=white) | Análise estática de código, utilizada para garantir qualidade, cobertura de testes e rastreamento de code smells no backend. |
| ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white) | Framework de testes utilizado para cobertura unitária, de integração e de sistema no backend Django. |
| ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) | Ferramenta de comunicação utilizada para interação contínua com a equipe da SIATT, alinhamento de requisitos e regras de negócio. |
| ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black) | Documentação interativa da API, facilitando o entendimento e teste dos endpoints. |

---

## Metodologia

O projeto utilizou **metodologia ágil incremental**, com sprints validadas junto à equipe da SIATT via Slack:

- **Sprint 1:** Modelagem de dados do backend (projetos, programas, materiais, fornecedores, tarefas, compras e estoque) e estruturação inicial da API.
- **Sprint 2:** Regras de negócio de custo e horas, endpoints analíticos de projeto e programa, e início da integração com o frontend.
- **Sprint 3:** Consolidação do pipeline de qualidade (SonarCloud, testes automatizados) e refinamento dos dashboards.

---

## Contribuições Individuais

Atuei como **Desenvolvedor Backend** e responsável pela **infraestrutura de qualidade** do projeto, sendo o principal responsável pela modelagem de dados, pelas regras de negócio do backend e pela estruturação do pipeline de testes e análise de código. Também contribuí com funcionalidades de frontend ligadas aos módulos que desenvolvi no backend.

---

<details>
<summary><b>Backend — Fundação de Dados e Regras de Negócio</b></summary>

- **Modelagem de Domínio:** Criação de praticamente todo o pacote `api/models/`, incluindo `projeto.py`, `programa.py`, `material.py`, `fornecedor.py`, `tarefa.py`, `tempo_tarefa.py`, `pedido_compra.py`, `solicitacao_compra.py`, `empenho_material.py`, `estoque_material_projeto.py` e `compras_projeto.py`, além das migrations 0002 e 0003.
- **Camada de Serviço:** Desenvolvimento de `api/services/projeto_svc.py` e `api/services/funcionario_svc.py`, concentrando as regras de negócio de projetos e funcionários.
- **Camada de API:** Desenvolvimento de `api/views/projeto_view.py` e `api/views/funcionario_view.py`, expondo os endpoints RESTful.
- **Utilitários:** Criação de `api/utils/pagination.py` para padronizar a paginação das respostas da API.
- **Regra de Custo (#33):** Correção do cálculo de custo total de projeto, ajustando a fórmula para o valor validado com o cliente, com testes cobrindo custo e tempo total do projeto.
- **Busca e Resumo de Programa (#22):** Endpoint de busca de programa com métricas agregadas de custo, horas e contagem de projetos.

</details>

<details>
<summary><b>Infraestrutura de Qualidade — CI/CD e Testes</b></summary>

- **SonarCloud:** Configuração da ferramenta do zero, com uma sequência de ajustes sucessivos até a estabilização completa do pipeline (correção de workflow e caminhos de cobertura, configuração para o submódulo de backend, envio do token ao workflow reutilizável, fixação da action por SHA completo, entre outros).
- **Pytest:** Criação do `pytest.ini`, do `conftest.py` geral e do `api/tests/conftest.py`.
- **Workflow:** Criação do `sonar-check.yml` para integração contínua da análise de qualidade.
- **Reorganização:** Estruturação da suíte de testes em camadas de integração e sistema.
- **Seed de Testes:** Criação do `seed_test.py` ao final do semestre, integrado ao pipeline.

</details>

<details>
<summary><b>Frontend — Componentes de Projeto e Programa</b></summary>

- **Estado Global:** Criação da store central `src/stores/projeto.ts`.
- **Componentes:** Desenvolvimento de `ProjetoSelector.vue`, `CustoCard.vue`, `MateriaisTable.vue`, `FuncionariosTable.vue`, `ProgramaCards.vue` e `ProgramaDonutChart.vue`.
- **Gráfico de Rosca (#24):** Implementação da distribuição de status dos projetos em gráfico de rosca (donut), incluindo backend e frontend.

</details>

---

## Funcionamento

A plataforma Lunae foi desenvolvida para atender diferentes níveis de análise dentro da SIATT, organizados em três visões que contemplam gestão operacional, tática e preditiva de projetos e programas.

<details>
<summary><b>Visão de Projetos</b></summary>

O usuário seleciona um projeto específico (busca por código/nome) e visualiza:
- **Cards de Resumo:** Custo Total (horas + materiais) e Tempo Total do projeto.
- **Tabela de Materiais:** Materiais consumidos, quantidades empenhadas e custo calculado.
- **Gráficos Burnup:** Evolução temporal do acúmulo de horas e custos, comparando projetos.
- **Gráfico de Barra:** Distribuição de horas por funcionário alocado.
- **Tabela de Funcionários:** Colaboradores, horas dedicadas e outros projetos em que atuam.

</details>

<details>
<summary><b>Visão de Programas</b></summary>

O usuário seleciona um programa específico e visualiza:
- **Cards de Resumo:** Custo Estimado, Custo Real, Horas Estimadas, Horas Reais e Total de Projetos.
- **Gráficos Burnup — Programa:** Comparação da evolução de horas e custos entre programas.
- **Tabela de Desvio de Hora:** Desempenho de cada projeto com indicadores de desvio entre horas realizadas e estimadas.
- **Gráfico de Barra:** Distribuição de horas por projeto do programa.
- **Gráfico de Rosca:** Distribuição percentual dos projetos por status.

</details>

<details>
<summary><b>Visão de Planejamento</b></summary>

Insights preditivos para antecipar necessidades de materiais e otimizar estoques e compras:
- **Alertas de Materiais:** Materiais críticos e em atenção com base em dias de cobertura e lead time.
- **Previsão de Próxima Compra:** Data ideal para novos pedidos, agrupados por janela de urgência.
- **Tabela de Risco de Falta:** Estoque atual, pedidos pendentes, consumo diário e status (Urgente, Atenção, OK).
- **Gráfico de Dispersão:** Comparação de fornecedores por lead time e valor total do pedido.

</details>

**Funcionalidades transversais:** Filtros globais (período, status, fornecedor, material) e exportação de dados em CSV, Excel e PDF.

---

## Aprendizados Efetivos

Este semestre representou um grande avanço técnico em backend e em cultura de qualidade de software. A configuração do SonarCloud do zero, apesar de trabalhosa, ensinou de forma prática como estruturar pipelines de CI/CD para análise estática de código e cobertura de testes, incluindo a resolução de problemas reais de configuração de workflow. A reorganização dos testes em camadas de integração e sistema trouxe mais clareza sobre a diferença entre os tipos de teste e sobre como estruturar um pacote de testes maduro em Django.

A correção da regra de negócio de custo total do projeto (#33) reforçou a importância de validar fórmulas de negócio junto ao cliente antes de implementar, e de cobrir esse tipo de regra com testes automatizados. A modelagem de praticamente todo o domínio de dados do backend aprofundou o entendimento sobre relacionamentos complexos no ORM do Django e sobre como estruturar migrations de forma incremental e segura.

---

## Hard Skills

| Tecnologia/Metodologia | Nota | Classificação | O que me falta |
| :--- | :--- | :--- | :--- |
| **Django (Models, Services, Views)** | ★★★★★ | Sei fazer com autonomia | Aprofundar em otimização de queries complexas e uso avançado de querysets. |
| **Modelagem de Dados Relacional** | ★★★★★ | Sei fazer com autonomia | Explorar estratégias avançadas de indexação e particionamento de tabelas. |
| **SonarCloud e CI/CD para Qualidade** | ★★★★☆ | Sei fazer com ajuda | Aprofundar em quality gates customizados e regras específicas por projeto. |
| **Pytest (unitário, integração e sistema)** | ★★★★☆ | Sei fazer com ajuda | Explorar testes de performance e testes de carga. |
| **PostgreSQL** | ★★★★☆ | Sei fazer com ajuda | Aprofundar em tuning de performance e otimização de índices. |
| **Vue.js (componentes e integração com API)** | ★★★☆☆ | Entendi | Aprofundar em gerenciamento de estado mais complexo e testes de componentes. |

---

## Soft Skills

| Soft Skill | Como desenvolvi neste projeto |
|:---|:---|
| **Responsabilidade Técnica** | Assumi a fundação de praticamente todo o domínio de dados do backend, garantindo consistência entre models, services e views. |
| **Resiliência e Persistência** | Enfrentei uma sequência de falhas sucessivas na configuração do SonarCloud até estabilizar completamente o pipeline de qualidade. |
| **Atenção a Detalhes** | Corrigi uma regra de negócio crítica de cálculo de custo (#33), validando a fórmula junto ao time antes de implementar e testar. |
| **Organização e Estruturação** | Reorganizei a suíte de testes em camadas de integração e sistema, facilitando a manutenção e o entendimento do pipeline por toda a equipe. |
| **Colaboração Técnica** | Trabalhei em conjunto com o time no desenvolvimento completo (backend e frontend) das issues #22 e #24. |

---

## Navegação entre Projetos

- [1º Semestre: Calculadora Científica](./1-semestre.md)
- [2º Semestre: Projeto Avaliador de Soft Skill](./2-semestre.md)
- [3º Semestre: Sistema de Ponto e Geração de Relatórios](./3-semestre.md)
- [4º Semestre: Monitoramento e Resposta a Incidentes](./4-semestre.md)
- [5º Semestre: Data Warehouse sobre Dados Operacionais da Empresa Parceira](./5-semestre.md)
- [6º Semestre: Sistema Inteligente de Gestão e Consulta de Documentos Técnicos](./6-semestre.md)

---

<div align="center">

### Desenvolvido durante a graduação em Banco de Dados

</div>
