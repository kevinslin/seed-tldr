---
id: linux.dm-tool
title: Dm Tool
desc: ''
updated: 1643803780823
created: 1643803780823
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dm-tool

> A tool to communicate with the display manager.
> More information: <https://manned.org/dm-tool>.

- Show the greeter while keeping current desktop session open and waiting to be restored upon authentication by logged in user:

`dm-tool switch-to-greeter`

- Lock the current session:

`dm-tool lock`

- Swicth to a specific user, showing an authentication prompt if required:

`dm-tool switch-to-user {{username}} {{session}}`

- Add a dynamic seat from within a running LightDM session:

`dm-tool add-seat {{xlocal}} {{name}}={{value}}`

