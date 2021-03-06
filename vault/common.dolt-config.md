---
id: common.dolt-config
title: Dolt Config
desc: ''
updated: 1623965306180
created: 1623965306180
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt config

> Read and write local (per repository) and global (per user) Dolt configuration variables.
> More information: <https://docs.dolthub.com/interfaces/cli#dolt-config>.

- List all local and global configuration options and their values:

`dolt config --list`

- Display the value of a local or global configuration variable:

`dolt config --get {{name}}`

- Modify the value of a local configuration variable, creating it if does not exist:

`dolt config --add {{name}} {{value}}`

- Modify the value of a global configuration variable, creating it if does not exist:

`dolt config --global --add {{name}} {{value}}`

- Delete a local configuration variable:

`dolt config --unset {{name}}`

- Delete a global configuration variable:

`dolt config --global --unset {{name}}`

