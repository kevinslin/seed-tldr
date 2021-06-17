---
id: common.pg_ctl
title: Pg_ctl
desc: ''
updated: 1623965016142
created: 1623965016142
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pg_ctl

> Utility for controlling a PostgreSQL server and database cluster.
> More information: <https://www.postgresql.org/docs/current/app-pg-ctl.html>.

- Initialize a new PostgreSQL database cluster:

`pg_ctl -D {{data_directory}} init`

- Start a PostgreSQL server:

`pg_ctl -D {{data_directory}} start`

- Stop a PostgreSQL server:

`pg_ctl -D {{data_directory}} stop`

- Restart a PostgreSQL server:

`pg_ctl -D {{data_directory}} restart`

- Reload the PostgreSQL server configuration:

`pg_ctl -D {{data_directory}} reload`

