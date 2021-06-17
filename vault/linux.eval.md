---
id: linux.eval
title: Eval
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eval

> Execute arguments as a single command in the current shell and return its result.

- Call `echo` with the "foo" argument:

`eval "{{echo foo}}"`

- Set a variable in the current shell:

`eval "{{foo=bar}}"`

