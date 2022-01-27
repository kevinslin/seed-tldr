---
id: linux.groupadd
title: Groupadd
desc: ''
updated: 1643318158468
created: 1643318158468
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# groupadd

> Add user groups to the system.
> See also: `groups`, `groupdel`, `groupmod`.
> More information: <https://manned.org/groupadd>.

- Create a new group:

`sudo groupadd {{group_name}}`

- Create a new system group:

`sudo groupadd --system {{group_name}}`

- Create a new group with the specific groupid:

`sudo groupadd --gid {{id}} {{group_name}}`

