---
id: common.doas
title: Doas
desc: ''
updated: 1623965016119
created: 1623965016119
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doas

> Executes a command as another user.
> More information: <https://man.openbsd.org/doas>.

- Run a command as root:

`doas {{command}}`

- Run a command as another user:

`doas -u {{user}} {{command}}`

- Launch the default shell as root:

`doas -s`

- Parse a config file and check if the execution of a command as another user is allowed:

`doas -C {{config_file}} {{command}}`

- Make `doas` request a password even after it was supplied earlier:

`doas -L`

