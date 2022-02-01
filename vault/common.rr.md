---
id: common.rr
title: Rr
desc: ''
updated: 1642441815066
created: 1642441815066
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rr

> Debugging tool designed to record and replay program execution.
> More information: <https://rr-project.org/>.

- Record an application:

`rr record {{path/to/binary --arg1 --arg2}}`

- Replay latest recorded execution:

`rr replay`

