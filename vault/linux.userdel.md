---
id: linux.userdel
title: Userdel
desc: ''
updated: 1623965306231
created: 1623965306231
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# userdel

> Remove a user account or remove a user from a group.
> Note: all commands must be executed as root.
> More information: <https://manned.org/userdel>.

- Remove a user:

`userdel {{name}}`

- Remove a user along with their home directory and mail spool:

`userdel --remove {{name}}`

- Remove a user from a group:

`userdel {{name}} {{group}}`

- Remove a user in other root directory:

`userdel --root {{path/to/other/root}} {{name}}`

