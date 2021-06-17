---
id: linux.groupmod
title: Groupmod
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# groupmod

> Modify existing user groups in the system.
> More information: <https://manned.org/groupmod>.

- Change the group name:

`groupmod -n {{new_group_name}} {{old_group_name}}`

- Change the group id:

`groupmod -g {{new_group_id}} {{old_group_name}}`

