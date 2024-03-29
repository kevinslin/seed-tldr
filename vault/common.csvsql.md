---
id: common.csvsql
title: Csvsql
desc: ''
updated: 1642441815005
created: 1642441815005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvsql

> Generate SQL statements for a CSV file or execute those statements directly on a database.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvsql.html>.

- Generate a `CREATE TABLE` SQL statement for a CSV file:

`csvsql {{path/to/data.csv}}`

- Import a CSV file into an SQL database:

`csvsql --insert --db "{{mysql://user:password@host/database}}" {{data.csv}}`

- Run an SQL query on a CSV file:

`csvsql --query "{{select * from 'data'}}" {{data.csv}}`

