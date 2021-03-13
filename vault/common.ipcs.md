---
id: common.ipcs
title: Ipcs
desc: ''
updated: 1615663978720
created: 1615663978720
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipcs

> Display information about resources used in IPC (Inter-process Communication).

- Specific information about the Message Queue which has the id 32768:

`ipcs -qi 32768`

- General information about all the IPC:

`ipcs -a`

