---
id: common.sequelize
title: Sequelize
desc: ''
updated: 1642441815068
created: 1642441815068
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sequelize

> Promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.
> More information: <https://sequelize.org/>.

- Create a model with 3 fields and a migration file:

`sequelize model:generate --name {{table_name}} --attributes {{field1:integer,field2:string,field3:boolean}}`

- Run the migration file:

`sequelize db:migrate`

- Revert all migrations:

`sequelize db:migrate:undo:all`

- Create a seed file with the specified name to populate the database:

`sequelize seed:generate --name {{seed_filename}}`

- Populate database using all seed files:

`sequelize db:seed:all`

