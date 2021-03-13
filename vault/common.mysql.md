---
id: common.mysql
title: Mysql
desc: ''
updated: 1615655543072
created: 1615655543072
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mysql

> The MySQL command-line tool.
> More information: <https://www.mysql.com/>.

- Connect to a database:

`mysql {{database_name}}`

- Connect to a database, user will be prompted for a password:

`mysql -u {{user}} --password {{database_name}}`

- Connect to a database on another host:

`mysql -h {{database_host}} {{database_name}}`

- Connect to a database through a Unix socket:

`mysql --socket {{path/to/socket.sock}}`

- Execute SQL statements in a script file (batch file):

`mysql -e "source {{filename.sql}}" {{database_name}}`

- Restore a database from a backup created with `mysqldump` (user will be prompted for a password):

`mysql --user {{user}} --password {{database_name}} < {{path/to/backup.sql}}`

- Restore all databases from a backup (user will be prompted for a password):

`mysql --user {{user}} --password < {{path/to/backup.sql}}`

