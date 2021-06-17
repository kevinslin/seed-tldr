---
id: common.id
title: Id
desc: ''
updated: 1623965306192
created: 1623965306192
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# id

> Display current user and group identity.
> More information: <https://www.gnu.org/software/coreutils/id>.

- Display current user's id (UID), group id (GID) and groups to which they belong:

`id`

- Display the current user identity as a number:

`id -u`

- Display the current group identity as a number:

`id -g`

- Display an arbitrary user's id (UID), group id (GID) and groups to which they belong:

`id {{username}}`

