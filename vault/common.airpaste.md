---
id: common.airpaste
title: Airpaste
desc: ''
updated: 1623965016111
created: 1623965016111
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airpaste

> Share messages and files on the same network using mDNS.
> More information: <https://github.com/mafintosh/airpaste>.

- Wait for a message and display it when received:

`airpaste`

- Send text:

`echo {{text}} | airpaste`

- Send a file:

`airpaste < {{path/to/file}}`

- Receive a file:

`airpaste > {{path/to/file}}`

- Create or join a channel:

`airpaste {{channel_name}}`

