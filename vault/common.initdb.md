---
id: common.initdb
title: Initdb
desc: ''
updated: 1642441815035
created: 1642441815035
stub: false
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

