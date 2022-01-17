---
id: common.eval
title: Eval
desc: ''
updated: 1642441815013
created: 1642441815013
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eval

> Execute arguments as a single command in the current shell and return its result.
> More information: <https://manned.org/eval>.

- Call `echo` with the "foo" argument:

`eval "{{echo foo}}"`

- Set a variable in the current shell:

`eval "{{foo=bar}}"`

