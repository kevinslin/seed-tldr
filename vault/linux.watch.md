---
id: linux.watch
title: Watch
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
# watch

> Execute a command repeatedly, and monitor the output in full-screen mode.

- Monitor files in the current directory:

`watch {{ls}}`

- Monitor disk space and highlight the changes:

`watch -d {{df}}`

- Monitor "node" processes, refreshing every 3 seconds:

`watch -n {{3}} "{{ps aux | grep node}}"`

