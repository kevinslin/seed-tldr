---
id: common.mysqld
title: Mysqld
desc: ''
updated: 1642441815049
created: 1642441815049
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mysqld

> Start the MySQL database server.
> More information: <https://dev.mysql.com/doc/refman/en/mysqld.html>.

- Start the MySQL database server:

`mysqld`

- Start the server, printing error messages to the console:

`mysqld --console`

- Start the server, saving logging output to a custom log file:

`mysqld --log={{path/to/file.log}}`

- Print the default arguments and their values and exit:

`mysqld --print-defaults`

- Start the server, reading arguments and values from a file:

`mysqld --defaults-file={{path/to/file}}`

- Start the server and listen on a custom port:

`mysqld --port={{port}}`

- Show all help options and exit:

`mysqld --verbose --help`

