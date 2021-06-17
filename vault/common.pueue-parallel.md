---
id: common.pueue-parallel
title: Pueue Parallel
desc: ''
updated: 1623965306206
created: 1623965306206
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pueue parallel

> Set the amount of allowed parallel tasks.
> More information: <https://github.com/Nukesor/pueue>.

- Set the maximum number of tasks allowed to run in parallel, in the default group:

`pueue parallel {{max_number_of_parallel_tasks}}`

- Set the maximum number of tasks allowed to run in parallel, in a specific group:

`pueue parallel --group {{group_name}} {{maximum_number_of_parallel_tasks}}`

