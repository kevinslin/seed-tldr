---
id: common.batch
title: Batch
desc: ''
updated: 1646802118614
created: 1646802118614
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# batch

> Execute commands at a later time when the system load levels permit.
> Service atd (or atrun) should be running for the actual executions.
> More information: <https://manned.org/batch>.

- Execute commands from standard input (press `Ctrl + D` when done):

`batch`

- Execute a command from standard input:

`echo "{{./make_db_backup.sh}}" | batch`

- Execute commands from a given file:

`batch -f {{path/to/file}}`

