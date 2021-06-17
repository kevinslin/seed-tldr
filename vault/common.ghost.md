---
id: common.ghost
title: Ghost
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ghost

> A blogging platform and headless CMS.
> More information: <https://ghost.org>.

- Install Ghost in the current directory:

`ghost install`

- Start an instance of Ghost:

`ghost start`

- Restart the Ghost instance:

`ghost restart`

- Check the system for any potential hiccups when on install or update of Ghost:

`ghost doctor`

- View the logs of a Ghost instance:

`ghost log {{name}}`

- Run a Ghost instance directly (used by process managers and for debugging):

`ghost run`

- View running Ghost processes:

`ghost ls`

- View or edit Ghost configuration:

`ghost config {{key}} {{value}}`

