---
id: common.createdb
title: Createdb
desc: ''
updated: 1646866913616
created: 1646866913616
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# createdb

> Create a PostgreSQL database.
> More information: <https://www.postgresql.org/docs/current/app-createdb.html>.

- Create a database owned by the current user:

`createdb {{database_name}}`

- Create a database owned by a specific user with a description:

`createdb --owner={{username}} {{database_name}} '{{description}}'`

- Create a database from a template:

`createdb --template={{template_name}} {{database_name}}`

