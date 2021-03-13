---
id: common.id
title: Id
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# id

> Display current user and group identity.

- Display current user's id (UID), group id (GID) and groups to which they belong:

`id`

- Display the current user identity as a number:

`id -u`

- Display the current group identity as a number:

`id -g`

- Display an arbitrary user's id (UID), group id (GID) and groups to which they belong:

`id {{username}}`

