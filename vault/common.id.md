---
id: common.id
title: Id
desc: ''
updated: 1642441815034
created: 1642441815034
stub: false
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

- Display current user's ID (UID), group ID (GID) and groups to which they belong:

`id`

- Display the current user identity as a number:

`id -u`

- Display the current group identity as a number:

`id -g`

- Display an arbitrary user's ID (UID), group ID (GID) and groups to which they belong:

`id {{username}}`

