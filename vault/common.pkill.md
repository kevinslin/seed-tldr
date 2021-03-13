---
id: common.pkill
title: Pkill
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkill

> Signal process by name.
> Mostly used for stopping processes.

- Kill all processes which match:

`pkill -9 {{process_name}}`

- Kill all processes which match their full command instead of just the process name:

`pkill -9 -f "{{command_name}}"`

- Send SIGUSR1 signal to processes which match:

`pkill -USR1 {{process_name}}`

