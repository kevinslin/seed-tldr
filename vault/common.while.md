---
id: common.while
title: While
desc: ''
updated: 1623965016155
created: 1623965016155
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# while

> Simple shell loop.

- Read stdin and perform an action on every line:

`while read line; do echo "$line"; done`

- Execute a command forever once every second:

`while :; do {{command}}; sleep 1; done`

