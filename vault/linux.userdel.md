---
id: linux.userdel
title: Userdel
desc: ''
updated: 1643318158495
created: 1643318158495
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# userdel

> Remove a user account or remove a user from a group.
> See also: `users`, `useradd`, `usermod`.
> More information: <https://manned.org/userdel>.

- Remove a user:

`sudo userdel {{username}}`

- Remove a user in other root directory:

`sudo userdel --root {{path/to/other/root}} {{username}}`

- Remove a user along with the home directory and mail spool:

`sudo userdel --remove {{username}}`

