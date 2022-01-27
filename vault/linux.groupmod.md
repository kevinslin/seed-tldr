---
id: linux.groupmod
title: Groupmod
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
# groupmod

> Modify existing user groups in the system.
> See also: `groups`, `groupadd`, `groupdel`.
> More information: <https://manned.org/groupmod>.

- Change the group name:

`sudo groupmod --new-name {{new_group}} {{group_name}}`

- Change the group id:

`sudo groupmod --gid {{new_id}} {{group_name}}`

