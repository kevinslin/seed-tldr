---
id: common.su
title: Su
desc: ''
updated: 1642441815073
created: 1642441815073
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# su

> Switch shell to another user.

- Switch to superuser (requires the root password):

`su`

- Switch to a given user (requires the user's password):

`su {{username}}`

- Switch to a given user and simulate a full login shell:

`su - {{username}}`

- Execute a command as another user:

`su - {{username}} -c "{{command}}"`

