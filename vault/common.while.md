---
id: common.while
title: While
desc: ''
updated: 1646143303360
created: 1646143303360
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# while

> Simple shell loop.
> More information: <https://manned.org/while>.

- Read stdin and perform an action on every line:

`while read line; do echo "$line"; done`

- Execute a command forever once every second:

`while :; do {{command}}; sleep 1; done`

