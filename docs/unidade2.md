---
title: Unidade 2
filename: unidade2.md
theme: jekyll-theme-architect
---

# O Projeto

## Versão 0.12
[Template do documento](https://docs.google.com/document/d/19BKNKYkIJTsT76UW47YChdQIxYEuyy6_r2m8N6qFm7M/edit#)

## Autores

### - João Ricardo Firmino de Almeida
### - Nicolas Roberto de Queiroz
### - Rafael Xavier Canabrava
### - Renann de Oliveira Gomes
### - Tiago Leão Buson

# Visão Geral do produto {#header}

## Declarção do problema

| O problema                   | É o descomprimento de atividades planejadas.                                                                                                    |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Afeta                        | Alunos e professores.                                                                                                                           |
| Cujo impacto é               | O descumprimento de uma ou mais atividades previamente planejada, levando a diminuição do rendimento ou a um completo fracasso com a atividade. |
| Uma solução de sucesso seria | Salvar lembretes com alguma mensagem escolhida pelo usuário e alerta-lo no horário desejado.                                                    |

## Declaração de posição de produto

1. **Qual é o produto que você se propõe a desenvolver?** Aplicativo de organização pessoal com ferramentas diversificadas, entre elas a organização interna entre grupos, agendamento de notificações e widget .
2. **O que torna este produto diferente dos seus concorrentes?** Poderá montar grupos com lista de tarefas separando assim cada tarefa em um contexto diferente.
3. **Quem são os usuários-alvo e clientes do produto?** Qualquer pessoa com interesse em ferramentas de organização, desde estudantes até pessoas com compromissos diversificados.
4. **Por que os clientes deveriam utilizar / comprar este produto?** Por ter uma interface intuitiva facilitando o uso, além dos lembretes em notificações por push, assim tornando muito mais prática a organização de listas, tarefas ou compromissos.

| Para                | Alunos e professores.                                                                         |
|---------------------|----------------------------------------------------------------------------------------------------------------------|
| Quem                | Deseja se organizar melhor ou que esqueça facilmente de seus afazeres                                                |
| O (nome do produto) | O Delfos                                                                                                             |
| Que                 | Ajuda a organizar e lembrar das tarefas, além de possuir outras ferramentas para auxiliar o usuário a se organizar.  |
| Ao contrário        |  Trello                                                                                                              |
| Nosso produto       | Não necessita de conexão com a internet para usar suas funcionalidades e possui uma interface de fácil interação.    |

## Objetivos do produto

De maneira intuitiva proporcionar ao cliente uma forma de se organizar e se lembrar de todas as suas atividades planejadas.

## Escopo do produto

### Requisitos Funcionais

- Deverá ser possível criar atividades
- Deverá ser possível deletar atividades
- Deverá ser possível editar atividades
- Deverá ser possível buscar e filtrar atividades
- Deverá ser possível configurar um horário no qual será emitida uma notificação sobre determinada atividade
- Deverá ser possível agrupar atividades
- Deverá haver um calendário para que em cada dia possam ser adicionadas atividades
- Deverá ser possível configurar atividades para se repetir em determinados dias da semana até que o usuário a desmarque(ex.: lavar roupa toda segunda)



| N°  | Requisitos Funcionais	                                                             | Prioridade |
|-----|-----------------------------------------------------------------------------------|------------|
| RF1 | Deverá ser possível cadastrar atividades                                          | Alta       |
| RF2 | Deverá ser possível deletar atividades                                            | Alta       |
| RF3 | Deverá ser possível editar atividades                                             | Alta       |
| RF4 | Deverá ser possível visualizar atividades                                         | Alta       |
| RF5 | Deverá ser possível filtrar atividades                                            | Média      |
| RF6 | Deverá ser possível agrupar atividades                                            | Média      |
| RF7 | Deverá haver um calendário para que em cada dia possam ser adicionadas atividades | Baixa      |

Prioridades:
  - Alta - Funcionalidade básica e essencial para o sistema
  - Média - Funcionalidade importante
  - Baixa - Funcionalidade desejável e complementar ao sistema


### Requisitos Não-funcionais

- O app não precisará de conexão com a internet para funcionar
- Haverá disponibilidade tanto para sistemas Android quanto para IOS
- Ocupará no máximo 500 mb de  memória do dispositivo
- O app terá um widget para que fique destacado na área de trabalho
- O app deve ser desenvolvido em react-native
- O versionamento do app deve ser feito pelo GitHub
- A aplicação deve ser documentada através do GitPages


| Classificação  | Requisitos Não-funcionais                                          | Prioridade |
|----------------|--------------------------------------------------------------------|------------|
|  Implementação | A aplicação deve ser documentada através do GitPages               | Alta       |
| Implementação  | O app deve ser desenvolvido em react-native                        | Alta       |
| Implementação  | O versionamento do app deve ser feito pelo GitHub                  | Alta       |
| Portabilidade  | Haverá disponibilidade tanto para sistemas Android quanto para IOS | Alta       |
|  Produto       | Ocupará no máximo 500 mb de  memória do dispositivo                | Média      |
| Usabilidade    | O app não precisará de conexão com a internet para funcionar       | Média      |
| Funcionalidade | O app terá um widget para que fique destacado na área de trabalho  | Baixa      |

## Mínimo Produto Viável (MVP)

[Link Canvas MVP 1](https://miro.com/app/board/uXjVOK02Oh0=/)

# Abordagem de desenvolvimento de software

## Metodologia

Levando em consideração os prazos já existentes da matéria e os prazos curtos de entrega da mesma, foi decidido em grupo a abordagem de metodologia ágil. Com o escopo de projeto médio e sem diversas modificações. A escolha se deu em um método Iterativo e Incremental (Scrum), com sprints de uma semana.


O escopo do projeto a ser desenvolvido é médio, com uma equipe de cinco integrantes, todos com pouquíssima experiência com as tecnologias a serem utilizadas. Os integrantes do grupo trabalharão em todos os aspectos do projeto, como desenvolvedores fullstack. O projeto será desenvolvido em React Native, Typescript, e terá como objetivo ser um aplicativo mobile.
A comunicação do time será efetuada através do Whatsapp, e o gerenciamento do fluxo do projeto utilizando o Trello e o Google Doc, com a possibilidade de ser substituído pelo Zenhub se a equipe assim preferir. As sprints retro e review serão efetuadas ao final de cada sprint utilizando o Microsoft Teams, Discord ou Telegram. O design do produto será idealizado utilizando o Figma.
 

## Processo

|                     Atividade                     |                                                                        Objetivo                                                                        |           Papel           |
|:-------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------:|
| Definir requisitos                                | Deixar claro o que deve ser entregue em cada requisito                                                                                                 | Product Owner             |
| Organizar requisitos                              | Separar todos os requisitos em grupos de níveis de importância                                                                                         | Desenvolvedor             |
| Fazer protótipo inicial                           | Criar protótipo para facilitar a visualização e servir de guia para o processo de produção do produto final                                            | Equipe de Desenvolvimento |
| Organizar Sprint                                  | Organizar e dividir as tarefas a serem executadas a cada sprint                                                                                        | Equipe de Desenvolvimento |
| Executar Sprint                                   | Execução as tarefas definidas na organização das sprints                                                                                               | Equipe de Desenvolvimento |
| Teste dos requisitos produzidos                   | Testar e verificar a estabilidade e qualidade do grupo de requisitos produzidos                                                                        | Equipe de Desenvolvimento |
| Entrega do grupo de requisitos                    | Entregar e apresentar os requisitos produzidos e preparar possíveis modificações                                                                       | Equipe de Desenvolvimento |
| Entrega do produto final                          | Entrega do projeto final (MVPs) ao cliente                                                                                                             | Equipe de Desenvolvimento |
| Teste do produto final e verificação de qualidade | Testar e verificar se todos os requisitos iniciais foram contemplados e se as modificações requeridas durante o processo de entregas foram atendidas.  | Product Owner             |

# Procedimentos

|                  Atividade                 |                                                                               Método                                                                              |                 Ferramenta                |
|:------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------:|
| Realizar reuniões                          | Reuniões diárias por mensagens. Reuniões por vídeo chamada e compartilhamento de tela semanalmente                                                                | Microsoft Teams/Discord/Telegram/Whatsapp |
| Versionamento de código                    | Controlar as alterações feitas no projeto por cada integrante do grupo por meio de registros e principalmente as versões de cada entrega de grupo de requisitos   | Github                                    |
| Organizar execução do projeto              | Organizar etapas e andamento das tarefas a serem executadas. Além da formação de eventuais documentos de descrição e organização                                  | Google Doc e Trelo/Zenhub                 |
| Desenvolver protótipo inicial              | Criação de projeto na ferramenta Figma que ajudará a visualizar e talvez servir de guia para o desenvolvimento de cada grupo de requisitos                        | Figma                                     |
| Desenvolver interfaces de tela             | Criação das telas do produto e sua navegação entre elas                                                                                                           | React Native + Typescript                 |
| Desenvolver funcionalidades da aplicação   | Desenvolvimento das funções que o produto vai desempenhar                                                                                                         | React Native + Typescript                 |
| Verificar se os requisitos foram atendidos | Testar o produto em dispositivos reais e verificar se todas as funções estão de acordo com os requisitos                                                          | Expo                                      |

# Lições aprendidas

## Unidade 1

A primeira unidade deu ao grupo instrução para que fosse possível a escolha de uma metodologia de desenvolvimento, visto que nenhum dos integrantes possuía conhecimento sobre esse assunto e não sabia qual metodologia se encaixaria melhor no projeto.

## Unidade 2

A segunda unidade proporcionou ao grupo noções sobre a elicitação, análise, especificação e validação de requisitos, tópicos essenciais para a Engenharia de Requisitos. O backlog quanto o MVP nos dão uma direção para que não percamos tempo ou desenvolvamos um software que não resolva o problema identificado pela equipe.

## Unidade 3

Lições aprendidas na unidade 3

## Unidade 4

Lições aprendidas na unidade 4

## Unidade 5

Lições aprendidas na unidade 5

# Referências bibliográficas

## Referência

# [Video de apresentação](https://www.youtube.com/watch?v=BQ_ug8QKp8s&ab_channel=NicolasRoberto "Link do Youtube")

[Voltar ao inicio](#header)

[Voltar à página inicial](https://fgaunb-mds-gm.github.io/2021.2-Delfos/)
