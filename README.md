# Desafio Controle de Gastos 💰

Esse desafio tem por objetivo validar e treinar conceitos de sql através de um sistema simples de controle de gastos utilizando sqlite

## Instruções e Dicas

1. O banco de dados utilizado é o *Sqlite* o mesmo já foi criado no projeto é o arquivo `banco.db`.
2. Os scripts de criação devem ficar dentro do arquivo `criacao.sql`
3. Os scripts de dados devem ficar dentro do arquivo `dados.sql`
4. As consultas devem ficar dentro do arquivo `consultas.sql`

**Dica:** utiliza a extensão: [SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite) do visual studio code para manipular o mesmo

**Dica:** Utilize esse site para entender como criar tabelas e pegar algumas consultas prontas com as nunancias do Sqlite [SQLite Tutorial](https://www.sqlitetutorial.net/)

**Dica:** Crie um `fork` desse projeto para seu github para trabalhar e versionar seu desafio

**Dica:** Crie commits com alterações pequenas e pontuais e utilize o padrão de commit semantico para facilitar a visualização das suas alterações no github. [Referencia sobre commits semanticos](https://github.com/iuricode/padroes-de-commits)

## Funcionalidades

* O usuário pode visualizar suas informações com nome, email e objetivo financeiro
* O usuário pode criar, atualizar, visualizar ou remover suas contas
    * O usuário pode criar e atualizar a conta com instituição financeira, nome e cor
* O usuário pode criar, atualizar, visualizar ou remover suas categorias
    * O usuário pode criar e atualizar uma categoria com nome e cor
* O usuário pode criar, atualizar, visualizar ou remover suas transações
    * O usuário pode criar ou atualizar uma transação com descrição, valor, categoria, data de criação e a conta
    * O usuário deve inserir valor negativo para despesas e positivo para receitas

## Visualizações

1. O usuário pode visualizar suas informações pessoais;
2. O usuário pode visualizar suas contas com informação do saldo atual (soma das transações);
3. O usuário pode visualizar suas categorias;
4. O usuário pode visualizar suas transações com data de criação, descrição, nome da categoria, conta e valor em ordem decrecente da data de criação;
5. O usuário pode visualizar total de despesas por categoria, filtrando pela data de criação, ordenando por ordem alfabetica seguida do maior gasto para o menor;
6. O usuário pode visualizar sua frequencia despesas, somando os gastos por periodo e filtrando pela data de criação;
7. O usuário pode visualizar o total de receitas e despesas no periodo de um ano por mês;
8. O usuário pode visualizar o balanço mensal, ou seja, o total de receitas, total de despesas e por fim o valor de um menos o outro respectivamente.


## Tabelas

Utilize esse espaço para mapear as tabelas e campos que precisam ser criados

Exemplo:

### usuarios

| campo | tipo   |
| ----- | ------ |
| id    | int    |
| nome  | string |
| email | string |



*Boa sorte e aproveite o desafio 🍀*
