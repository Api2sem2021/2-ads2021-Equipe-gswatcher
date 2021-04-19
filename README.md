# 📦 Entrega: __Sprint 2__

Abaixo encontram-se todos os itens produzidos durante a __SPRINT 2__ conforme estabelecido previamente por meio do planejamento das entregas: 

## 1 - 📅 Planejamento da Sprint:

### 📋 Sprint Backlog

### User Stories

| ID     | Prioridade | User Story                       | Planning Poker                                                 |
| -------| ---------- | -------------------------------- | -------------------------------------------------------------- | 
| US_07  | Essencial  | Eu, como usuário, gostaria de ter todo o processo de desenvolvimento do projeto documentado | 13 |
| US_08  | Essencial  | Eu, como usuário, gostaria de ter os dados dos arquivos *__Jira__* e *__Trello__* unificados e armazenados em um banco de dados | 8 |
| US_09  | Essencial  | Eu, como usuário, gostaria de carragar os dados em formato *__.json__* na aplicação para gerar as visualizações | 13 |
| US_10  | Essencial  | Eu, como usuário, gostaria de saber quantas tasks *__completas__* e *__incompletas__* um projeto possui, para medir seu adamento | 8 |
| US_11  | Essencial  | Eu, como usuário, gostaria de visualizar as informações dos projetos *__armazenadas no banco de dados__* | 13 |
| US_12  | Importante | Eu, como usuário, gostaria de visualizar o *__total de horas trabalhadas__* em um projeto *__por período__* | 8 |
| US_13  | Importante | Eu, como usuário, gostaria de visualizar a *__porcentagem de tasks concluídas__* em um projeto | 8 |
| US_14  | Desejável  | Eu, como usuário, gostaria de visualizar quantos e quais desenvolvedores estão trabalhando em um projeto para saber quem são os envolvidos | 8 |

*A imagem abaixo mostra os itens do [__Product Backlog__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-1/documentation/%2303_backlog_v3.pdf) a serem desenvolvidos durante essa Sprint 2:*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/sprint_2_backlog.png)

### 📉 Burndown Chart

*O gráfico abaixo mostra o desempenho da equipe na realização das tarefas referentes a Sprint:*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/burndown_sprint2.png)

## 2 - 📂 Artefatos II: Documentação do Projeto

Acesse os documentos produzidos durante a Sprint 2 clicando nos links abaixo:

* [__Gerenciamento do Escopo__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Documentation/Gerenciamento%20do%20Escopo.pdf)
* [__Gerenciamento do Cronograma__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Documentation/Gerenciamento%20de%20Cronograma.pdf)
* [__Gerenciamento de Qualidade__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Documentation/Gerenciamento%20de%20Qualidade.pdf)
* [__Gerenciamento de Custo__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Documentation/Gerenciamento%20de%20Custo.pdf)
* [__Gerenciamento de Rh__](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Documentation/Gerenciamento%20de%20RH.pdf)

*Clique [aqui](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/tree/Sprint-1#1----artefatos-documenta%C3%A7%C3%A3o-do-projeto) para acessar os documentos produzidos anteriormente.*

## 3 - 💫 Implementações

Os gifs abaixo são referentes as implementações realizadas durante essa Sprint 2.

*Clique [aqui para visualizar o código](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/tree/Sprint-2/GSW_integrado/gswatcher)*

### 3.1 - 🔘 Botão de Upload de arquivo json

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/upload_button_mobile.gif)


### 3.2 - 📊 Tasks de um projeto: Gráfico de Barras

*Gráfico de barras que apresenta a contagem de tasks de acordo com seus status.*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2302_project_tasks_mobile.gif)

### 3.3 - 📈 Horas trabalhadas em um projeto: Gráfico de Linha

*Gráfico de linha que apresenta o total de horas trabalhadas no projeto por determinado período*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2303_total_hours_mobile.gif)

### 3.4 - 📋 Desenvolvedores em um projeto: Tabela

#### ✔️ Tasks Completas:

*Tabela/Lista que apresenta todos desenvolvedores do projeto, podendo ser ordenada por:*
> * *Nome*
> * *Total de Tasks Completas*
> * *Data de Início*
> * *Total de Horas*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2304_devs_completed_tasks_mobile.gif)

#### ❌ Tasks Abertas:

*Tabela/lista que apresenta todos os desenvolvedores do projeto, podendo ser ordenada por:*
> * *Nome*
> * *Total de Tasks Abertas*
> * *Data de Início*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2305_devs_incompleted_tasks_mobile.gif)

### 3.5 - 🍕 Porcentagem de tasks concluídas: Gráfico de Pizza

*Gráfico de Pizza que apresenta a porcentagem de Tasks Completas e Incompletas do projeto*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2306_percentage_mobile.gif)

### 3.6 - 🔗 Integração parcial da página Main com o Banco de Dados

* *Os botões de "My Projects":*
> * *__'project'__:* ordena os projetos por ordem alfabética
> * *__'total tasks'__:* ordena os projetos por ordem crescente de total de tasks

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/%2301_mainMobile.gif)

### 3.7 - 🖥️ Visão Geral da Aplicação em tela Desktop

*O Gif abaixo mostra de uma forma geral como a aplicação deve ser em telas Desktop*

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/geral_desktop.gif)

### 3.8 - :hammer_and_wrench: Rotas da API:

*O Gif a seguir demostra todas as rotas criadas que irão ser consumidas pelo front-end.*

Para visualizar o código da API, [clique aqui.](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/tree/Sprint-2/GSW_integrado/Nodejs)

![](https://github.com/vinicius-hso/api-fatec-2s-gswatcher/blob/Sprint-2/Images/Gif_API.gif)
