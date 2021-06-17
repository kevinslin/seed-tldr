---
id: common.sqlite3
title: Sqlite3
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sqlite3

> The command-line interface to SQLite 3, which is a self-contained file-based embedded SQL engine.
> More information: <https://sqlite.org>.

- Start an interactive shell with a new database:

`sqlite3`

- Open an interactive shell against an existing database:

`sqlite3 {{path/to/database.sqlite3}}`

- Execute an SQL statement against a database and then exit:

`sqlite3 {{path/to/database.sqlite3}} '{{SELECT * FROM some_table;}}'`

