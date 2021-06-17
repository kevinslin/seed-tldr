---
id: common.xephyr
title: Xephyr
desc: ''
updated: 1623965016156
created: 1623965016156
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Xephyr

> A nested X server that runs as an X application.

- Create a black window with display ID ":2":

`Xephyr -br -ac -noreset -screen {{800x600}} {{:2}}`

- Start an X application on the new screen:

`DISPLAY=:2 {{command_name}}`

