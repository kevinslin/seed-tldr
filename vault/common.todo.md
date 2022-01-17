---
id: common.todo
title: Todo
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# todo

> A simple, standards-based, cli todo manager.
> More information: <https://todoman.readthedocs.io>.

- List startable tasks:

`todo list --startable`

- Add a new task to the work list:

`todo new {{thing_to_do}} --list {{work}}`

- Add a location to a task with a given ID:

`todo edit --location {{location_name}} {{task_id}}`

- Show details about a task:

`todo show {{task_id}}`

- Mark tasks with the specified IDs as completed:

`todo done {{task_id1 task_id2 ...}}`

- Delete a task:

`todo delete {{task_id}}`

- Delete done tasks and reset the IDs of the remaining tasks:

`todo flush`

