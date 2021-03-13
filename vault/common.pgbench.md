---
id: common.pgbench
title: Pgbench
desc: ''
updated: 1615663978729
created: 1615663978729
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pgbench

> Run a benchmark test on PostgreSQL.
> More information: <https://www.postgresql.org/docs/10/pgbench.html>.

- Initialize a database with a scale factor of 50 times the default size:

`pgbench --initialize --scale={{50}} {{database_name}}`

- Benchmark a database with 10 clients, 2 worker threads, and 10,000 transactions per client:

`pgbench --clients={{10}} --jobs={{2}} --transactions={{10000}} {{database_name}}`

