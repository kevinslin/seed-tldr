---
id: common.watch
title: Watch
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# watch

> Execute a program periodically, showing output fullscreen.

- Repeatedly run a command and show the result:

`watch {{command}}`

- Re-run a command every 60 seconds:

`watch -n {{60}} {{command}}`

- Monitor the contents of a directory, highlighting differences as they appear:

`watch -d {{ls -l}}`

