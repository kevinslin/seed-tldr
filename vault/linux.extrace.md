---
id: linux.extrace
title: Extrace
desc: ''
updated: 1623965306222
created: 1623965306222
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# extrace

> Trace exec() calls.
> More information: <https://github.com/chneukirchen/extrace>.

- Trace all program executions occurring on the system:

`sudo extrace`

- Run a command and only trace descendants of this command:

`sudo extrace {{command}}`

- Print the current working directory of each process:

`sudo extrace -d`

- Resolve the full path of each executable:

`sudo extrace -l`

- Display the user running each process:

`sudo extrace -u`

