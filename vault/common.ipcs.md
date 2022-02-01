---
id: common.ipcs
title: Ipcs
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipcs

> Display information about resources used in IPC (Inter-process Communication).
> More information: <https://manned.org/ipcs>.

- Specific information about the Message Queue which has the ID 32768:

`ipcs -qi 32768`

- General information about all the IPC:

`ipcs -a`

