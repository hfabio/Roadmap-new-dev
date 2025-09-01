# Base de conhecimento para um engenheiro de software sênior  
**falar inglês é imprescindível**  
## Índice:
- [ferramentas](#ferramentas)
- [linguagens e marcação de texto](#linguagens-e-marcação-de-texto)
- [db](#db)
- [code-style](#code-style)
- [backend](#backend)
- [frontend](#frontend)
- [Soft skills](#soft-skills)
- [design patterns](##design-patterns)

## ferramentas
- Jira (ou trello, ou github projects, ou linear etc, **aprenda sobre scrum + kanban**)
- vscode (ou cursor)
- Postman (ou insomnia, ou thunderclient, mas alguma forma de **fazer requisições HTTP localmente e testar seus apps**)
- DBMS (escolha um, mas **recomendo o workbench**):
  - mysql workbench
  - dbeaver
  - sequel ace

## linguagens e marcação de texto  
- javascript (e typescript obviamente)
- python (é sempre útil, tanto para backend quanto para scripts auxiliares)
- golang (opcional, mas é interessante assim como o rust)
- bash
- sql
- json
- yaml (obrigatório em jobs do github actions, arquivos do serverless etc)
- toml (opcional)
- MarkDown
- HTML5
- CSS3

## db  
- redis
- mysql 8 OU postgres 16
- dynamoDB (opcional)

## code-style  
- prettier
- eslint
- editorconfig
- husky (opcional, mas é bom aprender)

## devops  
- containerização:
  - docker (aprenda sobre alpine linux, distroless, build em múltiplas etapas)
  - docker-compose
- github-actions
- github-pages (opcional, dificil você utilizar no dia-a-dia)
- aws:
  - lambda (leia sobre batch também)
  - s3
  - ecs
  - sqs

## backend  
- nodejs
- express
- jwt
- node:crypto
- mysql2
- knex (ou outro ORM/querybuilder como prisma, ou sequelize etc)
- para testes:
  - jest 
  - node test suite
  - cypress
  - fakerjs
- swagger
- puppeteer
- sentry
- datadog

## frontend  
- vite
- reactjs
- redux
- i18n
- jest (pro frontend com react-testing-library)
- sass
- storybook
- styled-components

## Programming skills  
- multithread / child process / fork / cluster
- async programming (async/await, promises)
- leetcode (utilize uma plataforma para treinar algoritmos, tipo leetcode/codewars/codesignal/hackerrank

## hard skills  
- D.R.Y
- SOLID
- clean code
- clean architecture
- system design
- event loop
- hoisting
- arquitetura de computadores
- notação assintótica (e complexidade de algoritmos, da uma lida [aqui](https://learnxinyminutes.com/pt-br/asymptotic-notation/))
- sistemas operacionais (entenda linha de comando e como funcionam coisas como: sistema de arquivo, scheduler, memória, gestão de recursos etc, e sim, eu recomendo linux.)

## Design patterns  
também conhecido como (padrão de projetos)
leia sobre eles, [aqui](https://refactoring.guru/pt-br/design-patterns) tem uma boa referência
- singleton
- decorator
- factory
- adapter
- facade
- repository
- dependency injection
- pubsub
- CQRS
