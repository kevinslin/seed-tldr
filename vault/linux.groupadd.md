---
id: linux.groupadd
title: Groupadd
desc: ''
updated: 1642441815096
created: 1642441815096
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
> More information: <https://manned.org/groupadd>.

- Create a new Linux group:

`groupadd {{group_name}}`

- Create new group with a specific groupid:

`groupadd {{group_name}} -g {{group_id}}`

