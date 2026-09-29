<div align="center">

# API 6º Semestre - 02/2026

<a href="https://github.com/Pragma-Co/indice" target="_blank">
  <img src="https://img.shields.io/badge/Repositório-555555?style=for-the-badge&logo=github&logoColor=white">
</a>

### Parceiro Acadêmico:
**FATEC São José dos Campos - Prof. Jessen Vidal**

### Empresa Parceira:
**Akaer**

</div>

---

## Resumo do Projeto

Desenvolvimento da plataforma **Índice** para a Akaer. A solução tem como objetivo otimizar a busca e o acesso a documentos e normas técnicas da empresa, que atualmente se encontram dispersos em um sistema onde os usuários consomem muito tempo até encontrar o documento que realmente atende sua demanda — muitas vezes sendo necessário ler páginas de diversos arquivos antes de identificar o correto. Por meio do uso de Inteligência Artificial e Machine Learning, o Índice estabelece correlações entre a pesquisa do usuário e os documentos que possam corresponder ao desejado, agilizando e tornando mais precisa a localização da informação. A plataforma conta com tela de pesquisa (campo textual e filtros pré-determinados), fluxo de upload de documentos em três etapas, listagens de documentos do usuário e do sistema, visualização de detalhes com controle de permissão de acesso, fluxo de nova revisão de documentos e telas administrativas para controle de permissões e de usuários. Dessa forma, além de acelerar a consulta, o Índice garante segurança e autorização no acesso aos documentos, permitindo que perfis autorizados decidam quem pode visualizar cada documento e estabeleçam a relação entre as áreas da empresa, apoiando a gestão documental e a tomada de decisão.

---

## Problema

A Akaer possui um sistema com diversos documentos e normas que seus usuários podem acessar. O problema atual está no tempo que os clientes demoram realizando buscas até chegar aos documentos que realmente precisam — muitas vezes é necessário ler páginas de diversos documentos até descobrir se aquele é o documento que vai atender sua demanda. Além disso, hoje os documentos não possuem segurança e autorização para serem visualizados, o que pode acarretar em problemas de segurança.

---

## Solução

Utilizando IA e machine learning, o sistema **Índice** monta correlações entre a pesquisa do usuário e os documentos que possam corresponder ao desejado. A plataforma dispõe de uma **tela de pesquisa** com campo textual e filtros pré-determinados, de um **fluxo de upload de documentos** e de **login com diferentes perfis de usuário**, de forma que alguns perfis possam controlar os demais e decidir níveis de autorização (quem pode ver qual documento) e a relação entre as áreas da empresa.

---

## Tecnologias Adotadas

<p>
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

**Vue 3 (TypeScript)** é o framework web utilizado para construir o frontend da plataforma, com foco na interatividade das telas de pesquisa, listagens e visualização de documentos. **Vite** é a ferramenta de build e servidor de desenvolvimento utilizada no frontend, proporcionando maior velocidade no desenvolvimento e no carregamento da aplicação. **Vitest** é o framework de testes utilizado no frontend para garantir a qualidade dos componentes e da lógica da interface. **Django** é o framework web em Python utilizado no backend para desenvolvimento da API, responsável pela lógica de negócio, autenticação, controle de permissões e gerenciamento dos documentos. **Pytest** é o framework de testes utilizado no backend para validação das regras de negócio e dos endpoints da API. **PostgreSQL** é o banco de dados relacional utilizado para armazenar os dados estruturados da plataforma, como usuários, permissões e metadados dos documentos. **MongoDB** é o banco de dados NoSQL utilizado para armazenar os documentos e conteúdos não estruturados, apoiando a busca e a correlação feita pela IA. **Docker** é a plataforma de containerização utilizada para padronizar o ambiente de desenvolvimento e facilitar o deploy da aplicação. **Figma** é a ferramenta de design utilizada para prototipação e validação da interface com o cliente. **Git** é o sistema de controle de versionamento distribuído utilizado para gerenciar o código-fonte do projeto, permitindo rastreamento de alterações, trabalho em paralelo por meio de branches e colaboração eficiente entre os membros da equipe. **GitHub** é a plataforma de hospedagem de repositórios Git utilizada para armazenar o código-fonte do projeto, gerenciar issues, pull requests, revisões de código e a documentação do projeto na Wiki. **Jira** é a ferramenta de gestão ágil utilizada para o quadro Scrum, rastreamento de tarefas, colunas de fluxo (Ready for Sprint, Blocked, Done) e definição de prioridades pelo PO. **Swagger** é a documentação interativa da API, facilitando o entendimento e teste dos endpoints.

---

## Metodologia

O projeto utiliza **Scrum**, com sprints de três semanas e cerimônias formalizadas na Wiki do repositório (Team Agreements, Team Roles, Sprint Documentation). A Sprint 1 está em andamento, com foco na definição de processo, papéis e capacidade da equipe antes da entrega técnica.

---

## Contribuições Individuais

Atuo como **Scrum Master** neste projeto. Nesta Sprint 1, minha atuação está concentrada exclusivamente na condução do processo ágil — estruturação de cerimônias, papéis, regras de convivência do time e acompanhamento de impedimentos —, sem contribuição técnica de código neste momento.

---

<details>
<summary><b>Estruturação de Papéis e Processo (Team Roles)</b></summary>

Documentei e formalizei as responsabilidades de cada papel do time na Wiki do projeto: Developers, PO (Product Owner) e SM (Scrum Master). Defini as regras de fluxo de trabalho dos desenvolvedores, como só iniciar uma tarefa com o DoR completo, priorizar cards da coluna "Ready for Sprint" conforme o PO, trabalhar em uma tarefa por vez, priorizar code review antes de puxar nova tarefa, e mover para "Blocked" em caso de dependência. Defini também o papel do PO, com o acionamento de cancelamento e replanejamento de Sprint caso um card do Goal fique bloqueado e não possa ser entregue, além do meu próprio papel de SM, focado no acompanhamento de impedimentos nas tarefas da sprint atual e das próximas, atuando como ponto de apoio para garantir que o produto avance conforme o esperado. Levantei e registrei a capacidade do time (Team Capacity) para a Sprint 1, consolidando as horas semanais dedicadas ao projeto por cada membro fora do horário de Fatec, totalizando 183h de capacidade para a sprint.

</details>

<details>
<summary><b>Definição de Acordos de Time (Team Agreements)</b></summary>

Criei o documento de Acordo de Time, estabelecendo regras de conduta, responsabilidades e consequências para o não cumprimento de obrigações durante as Sprints, com a entrega obrigatória de tarefas como pilar central do projeto. Estruturei um sistema de pontuação por infrações em cerimônias (ausência em daily presencial ou online, Sprint Planning, Sprint Review e Retrospectiva), com pontos que resetam a cada Sprint, além dos respectivos limites e consequências (advertência verbal, advertência formal com plano de recuperação, e desligamento do grupo por quebra do acordo). Defini também a cadência de dailies do time: uma daily presencial semanal e duas dailies escritas e assíncronas, das quais sou responsável por abrir a cerimônia às 8h e encerrar às 23h59, além do processo de assembleia para casos extraordinários não previstos nas regras. Fico responsável pelo registro da pontuação do time em planilha/software compartilhado, com prazo de 24h após o fim de cada cerimônia para atualização da documentação.

</details>

<details>
<summary><b>Acompanhamento de Impedimentos</b></summary>

Atuação como ponto de apoio do time para identificação e remoção de impedimentos nas tarefas da sprint atual e das próximas sprints, com foco em garantir que o desenvolvimento do produto avance sem bloqueios prolongados.

</details>

<details>
<summary><b>Contribuições Futuras (TODO)</b></summary>

Como o projeto ainda está em andamento, novas contribuições estão previstas para as próximas sprints, com destaque para a documentação do Sprint Backlog, condução formal das cerimônias de Planning, Review e Retrospectiva, e acompanhamento do burndown das próximas sprints.

</details>

---

## Funcionamento

> O projeto ainda está em desenvolvimento. As descrições abaixo refletem o que foi planejado pelo time. Imagens e vídeos serão adicionados futuramente, pois muitas telas ainda sofrerão alterações.

### Tela Inicial e Pesquisa

A tela inicial conta com um campo de pesquisa aberto e filtros simples. Abaixo do campo de busca, é exibido o histórico das últimas mudanças realizadas pelo usuário logado no sistema — geralmente relacionadas ao upload de documentos.

### Fluxo de Upload de Documentos

O upload de documentos é realizado em **três passos**:

1. **Passo 1**: Upload de um ou mais documentos;
2. **Passo 2**: Preenchimento das informações a respeito dos documentos;
3. **Passo 3**: Revisão das informações para conferência antes da conclusão.

### Listagens de Documentos

A **tela de listagem de documentos do usuário** exibe todos os documentos que o próprio usuário fez upload, enquanto a **tela de listagem de documentos do sistema** exibe todos os documentos disponíveis no sistema.

### Detalhes e Permissões

Ao tentar acessar o detalhe de um documento (em qualquer uma das telas de listagem), a visualização só é exibida caso o usuário tenha permissão de acesso. Caso tenha, ele pode visualizar as imagens e também clicar no botão "Nova Revisão", onde poderá anexar novos documentos para gerar uma nova revisão daquele documento.

### Telas Administrativas

A **tela de controle de permissões**, acessível apenas por usuários com permissão adequada, permite permitir ou negar a visualização de um usuário a um documento que foi previamente solicitado. Já a **tela de controle de usuários** permite controlar a área do usuário, bem como ativar ou inativar usuários.

---

## Aprendizados Efetivos

A atuação como Scrum Master no projeto **Índice** tem proporcionado experiência prática em um ambiente corporativo real, com a parceira Akaer, envolvendo a estruturação de um processo ágil do zero para um time recém-formado. Este semestre reforçou a importância de formalizar papéis, regras de convivência e critérios de capacidade antes do início do desenvolvimento técnico, servindo como base para o alinhamento de expectativas entre PO, desenvolvedores e cliente. A criação do Acordo de Time e do sistema de pontuação por cerimônias trouxe aprendizado prático sobre como equilibrar disciplina de processo com senso de justiça e flexibilidade (por meio da assembleia para casos extraordinários), enquanto o acompanhamento de impedimentos aprofundou a visão sobre como um Scrum Master atua como facilitador, e não como gestor direto das entregas técnicas.

### Hard Skills

<table align="center">
    <tr>
      <th width="270px">Tecnologia/Metodologia</th>
      <th width="85px">Nota</th>
      <th width="200px">Classificação</th>
    </tr>
   <tr>
    <td>Scrum (papel de Scrum Master)</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Condução de Cerimônias Ágeis</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Jira (gestão de board e fluxo)</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Documentação de Processo (Wiki)</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Git</td>
    <td>★★★★★</td>
    <td>Sei fazer com autonomia</td>
   </tr>
   <tr>
    <td>Vue.js</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Django</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>PostgreSQL</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>TypeScript</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Vitest</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
   <tr>
    <td>Pytest</td>
    <td>★★★★☆</td>
    <td>Sei fazer com ajuda</td>
   </tr>
   <tr>
    <td>Figma</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
   <tr>
    <td>Vite</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
   <tr>
    <td>MongoDB</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
   <tr>
    <td>Docker</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
   <tr>
    <td>Swagger</td>
    <td>★★★☆☆</td>
    <td>Entendi</td>
   </tr>
</table>

---

### Soft Skills

<table align="center">
    <tr>
      <th width="270px">Habilidade</th>
      <th width="280px">Descrição</th>
    </tr>
    <tr>
      <td>Facilitação e Liderança Servidora</td>
      <td>Conduzi a estruturação inicial do processo ágil do time, definindo papéis, regras e cerimônias, atuando como facilitador e não como gestor direto das entregas técnicas.</td>
    </tr>
    <tr>
      <td>Mediação de Conflitos</td>
      <td>Estruturei um sistema de pontuação por infrações com limites claros e um processo de assembleia para casos extraordinários, equilibrando disciplina de processo com senso de justiça no time.</td>
    </tr>
    <tr>
      <td>Organização e Disciplina de Processo</td>
      <td>Assumi a responsabilidade de abrir e encerrar as dailies assíncronas dentro do prazo, além de registrar e atualizar a pontuação do time em até 24h após cada cerimônia.</td>
    </tr>
    <tr>
      <td>Visão Sistêmica de Produto</td>
      <td>Acompanho impedimentos nas tarefas da sprint atual e das próximas, atuando como ponto de apoio para garantir que o produto avance conforme o esperado, mesmo sem atuação técnica direta.</td>
    </tr>
</table>

---

## Navegação entre Projetos

* [1º Semestre: Calculadora Científica](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-1-semestre.md)
* [2º Semestre: Avaliador de Soft Skill](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-2-semestre.md)
* [3º Semestre: Sistema de Ponto e Geração de Relatórios](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-3-semestre.md)
* [4º Semestre: Monitoramento e Resposta a Incidentes](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-4-semestre.md)
* [5º Semestre: Data Warehouse sobre Dados Operacionais da Empresa Parceira](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-5-semestre.md)
* [6º Semestre: Sistema Inteligente de Gestão e Consulta de Documentos Técnicos](https://github.com/augustopiatto/portfolio-fatec/blob/main/projetos/API-6-semestre.md)

---

<p align="center">
  Desenvolvido durante a graduação em Banco de Dados
</p>
