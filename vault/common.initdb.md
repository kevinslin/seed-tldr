---
id: common.initdb
title: Initdb
desc: ''
updated: 1623965306193
created: 1623965306193
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# initdb

> Create a PostgreSQL database on disk.
> More information: <https://www.postgresql.org/docs/9.5/app-initdb.html>.

- Create a database at `/usr/local/var/postgres`:

`initdb -D /usr/local/var/postgres`

