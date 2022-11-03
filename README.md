# desafio-controle-gastos

Esse desafio tem por objetivo validar e treinar conceitos de sql através de um sistema simples de controle de gastos utilizando sqlite

## Instruções e Dicas

1. O banco de dados utilizado é o *Sqlite* o mesmo já foi criado no projeto é o arquivo `banco.db`. Dica: utiliza a extensão: [SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite) do visual studio code para manipular o mesmo

2. Os scripts de criação devem ficar dentro do arquivo `criacao.sql`

3. Os scripts de dados devem ficar dentro do arquivo `dados.sql`

4. As consultas devem ficar dentro do arquivo `consultas.sql`

Dica: Utilize esse site para entender como criar tabelas e pegar algumas consultas prontas com as nunancias do Sqlite [SQLite Tutorial](https://www.sqlitetutorial.net/)

## Funcionalidades

1. O usuário pode visualizar suas informações (Nome, email e objetivo financeiro)
2. O usuário pode criar, atualizar, visualizar ou remover suas contas
2.1. O usuário pode criar e atualizar a conta com Instituição Financeira, Nome e Cor
3. O usuário pode criar, atualizar, visualizar ou remover suas categorias
3.1. O usuário pode criar e atualizar uma categoria com nome e cor
4. O usuário pode criar, atualizar, visualizar ou remover suas transações
4.1. O usuário pode criar ou atualizar uma transação com descrição, valor(+/-), categoria, data de criação e a conta
4.2. O usuário deve inserir valor negativo para despesas e positivo para receitas

## Visualizações

1. O usuário pode visualizar suas informações pessoais
2. O usuário pode visualizar suas contas com informação do saldo atual (soma das transações)
3. O usuário pode visualizar suas categorias
4. O usuário pode visualizar suas transações com data de criação, descrição, nome da categoria, conta e valor em ordem decrecente da data de criação
5. O usuário pode visualizar os gastos totais por categoria, filtrando pela data de criação
6. O usuário pode visualizar sua frequencia de gastos, somando os gastos por dia e filtranso pela data de criação
7. O usuário pode visualizar o total de receitas e despesas por ano somando o total por mês


## Tabelas

// Todo
