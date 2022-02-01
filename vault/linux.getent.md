---
id: linux.getent
title: Getent
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
# getent

> Get entries from Name Service Switch libraries.
> More information: <https://manned.org/getent>.

- Get list of all groups:

`getent group`

- See the members of a group:

`getent group {{group_name}}`

- Get list of all services:

`getent services`

- Find a username by UID:

`getent passwd 1000`

- Perform a reverse DNS lookup:

`getent hosts {{host}}`

