---
id: common.topydo
title: Topydo
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# topydo

> A todo list application that uses the todo.txt format.
> More information: <https://github.com/topydo/topydo>.

- Add a todo to a specific project with a given context:

`topydo add "{{todo_message}} +{{project_name}} @{{context_name}}"`

- Add a todo with a due date of tomorrow with a priority of `A`:

`topydo add "(A) {{todo _message}} due:{{1d}}"`

- Add a todo with a due date of friday:

`topydo add "{{todo_message}} due:{{fri}}"`

- Add a non-strict repeating todo (next due = now + rec):

`topydo add "water flowers due:{{mon}} rec:{{1w}}"`

- Add a strict repeating todo (next due = currentdue + rec):

`topydo add "{{todo_message}} due:{{2020-01-01}} rec:{{+1m}}"`

- Revert the last `topydo` command executed:

`topydo revert`

