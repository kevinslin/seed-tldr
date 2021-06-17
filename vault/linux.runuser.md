---
id: linux.runuser
title: Runuser
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# runuser

> Run commands as a specific user and group without asking for password (needs root privileges).

- Run command as a different user:

`runuser {{user}} -c '{{command}}'`

- Run command as a different user and group:

`runuser {{user}} -g {{group}} -c '{{command}}'`

- Start a login shell as a specific user:

`runuser {{user}} -l`

- Specify a shell for running instead of the default shell (also works for login):

`runuser {{user}} -s {{/bin/sh}}`

- Preserve the entire environment of root (only if `--login` is not specified):

`runuser {{user}} --preserve-environment -c '{{command}}'`

