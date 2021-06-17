---
id: common.jhat
title: Jhat
desc: ''
updated: 1623965306193
created: 1623965306193
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jhat

> Java Heap Analysis Tool.

- Analyze a heap dump (from jmap), view via http on port 7000:

`jhat {{dump_file.bin}}`

- Analyze a heap dump, specifying an alternate port for the http server:

`jhat -p {{port}} {{dump_file.bin}}`

- Analyze a dump letting jhat use up to 8GB RAM (2-4x dump size recommended):

`jhat -J-mx8G {{dump_file.bin}}`

