---
id: linux.mycli
title: Mycli
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mycli

> A CLI for MySQL, MariaDB, and Percona with auto-completion and syntax highlighting.
> More information: <https://manned.org/mycli>.

- Connect to a database with the currently logged in user:

`mycli {{database_name}}`

- Connect to a database with the specified user:

`mycli -u {{user}} {{database_name}}`

- Connect to a database on the specified host with the specified user:

`mycli -u {{user}} -h {{host}} {{database_name}}`

