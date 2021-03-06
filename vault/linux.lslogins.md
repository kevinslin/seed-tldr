---
id: linux.lslogins
title: Lslogins
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lslogins

> Show information about users on a Linux system.
> More information: <https://man7.org/linux/man-pages/man1/lslogins.1.html>.

- Display users in the system:

`lslogins`

- Display users belonging to a specific group:

`lslogins --groups={{groups}}`

- Display user accounts:

`lslogins --user-accs`

- Display last logins:

`lslogins --last`

- Display system accounts:

`lslogins --system-accs`

- Display supplementary groups:

`lslogins --supp-groups`

