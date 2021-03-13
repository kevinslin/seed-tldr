---
id: linux.groupmod
title: Groupmod
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# groupmod

> Modify existing user groups in the system.

- Change the group name:

`groupmod -n {{new_group_name}} {{old_group_name}}`

- Change the group id:

`groupmod -g {{new_group_id}} {{old_group_name}}`

