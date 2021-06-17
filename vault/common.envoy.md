---
id: common.envoy
title: Envoy
desc: ''
updated: 1623965016123
created: 1623965016123
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# envoy

> A PHP-based task manager for Laravel remote servers.
> More information: <https://laravel.com/docs/envoy>.

- Initialise a configuration file:

`envoy init {{host_name}}`

- Run a task:

`envoy run {{task_name}}`

- Run a task from a specific project:

`envoy run --path {{path/to/directory}} {{task_name}}`

- Run a task and continue on failure:

`envoy run --continue {{task_name}}`

- Dump a task as a bash script for inspection:

`envoy run --pretend {{task_name}}`

- Connect to the specified server via SSH:

`envoy ssh {{server_name}}`

