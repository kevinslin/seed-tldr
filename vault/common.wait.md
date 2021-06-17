---
id: common.wait
title: Wait
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
# wait

> Wait for a process to complete before proceeding.

- Wait for a process to finish given its process ID (PID) and return its exit status:

`wait {{pid}}`

- Wait for all processes known to the invoking shell to finish:

`wait`

