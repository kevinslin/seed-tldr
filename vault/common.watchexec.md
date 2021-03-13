---
id: common.watchexec
title: Watchexec
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# watchexec

> Run arbitrary commands when files change.
> More information: <https://github.com/watchexec/watchexec>.

- Call `ls -la` when any file in the current directory changes:

`watchexec -- {{ls -la}}`

- Run `make` when any JavaScript, CSS and HTML files in the current directory change:

`watchexec --exts {{js,css,html}} make`

- Run `make` when any file in the `lib` or `src` subdirectories change:

`watchexec --watch {{lib}} --watch {{src}} {{make}}`

- Call/restart `my_server` when any file in the current directory change, sending `SIGKILL` to stop the child process:

`watchexec --restart --signal {{SIGKILL}} {{my_server}}`

