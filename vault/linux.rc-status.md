---
id: linux.rc-status
title: Rc Status
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rc-status

> Show status info about runlevels.
> See also `openrc`.

- Show a summary of services and their status:

`rc-status`

- Include services in all runlevels in the summary:

`rc-status --all`

- List services that have crashed:

`rc-status --crashed`

- List manually started services:

`rc-status --manual`

- List supervised services:

`rc-status --supervised`

- Get the current runlevel:

`rc-status --runlevel`

- List all runlevels:

`rc-status --list`

