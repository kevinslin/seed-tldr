---
id: linux.uuidd
title: Uuidd
desc: ''
updated: 1623965306231
created: 1623965306231
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uuidd

> Daemon for generating UUIDs.
> More information: <https://manned.org/uuidd>.

- Generate a random UUID:

`uuidd --random`

- Generate a bulk number of random UUIDs:

`uuidd --random --uuids {{number_of_uuids}}`

- Generate a time-based UUID, based on the current time and MAC address of the system:

`uuidd --time`

