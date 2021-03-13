---
id: common.airpaste
title: Airpaste
desc: ''
updated: 1615663978697
created: 1615663978697
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airpaste

> Share messages and files on the same network.

- Wait for message and display when received:

`airpaste`

- Send text:

`echo {{text}} | airpaste`

- Send file:

`airpaste < {{path/to/file}}`

- Receive file:

`airpaste > {{path/to/file}}`

- Create/Join channel:

`airpaste {{channel_name}}`

