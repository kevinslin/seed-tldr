---
id: common.gox
title: Gox
desc: ''
updated: 1623965306190
created: 1623965306190
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gox

> A tool for cross-compiling Go programs.
> More information: <https://github.com/mitchellh/gox>.

- Compile Go program in the current directory for all operating systems and architecture combinations:

`gox`

- Download and compile a Go program from a remote URL:

`gox {{url_1}} {{url_2}}`

- Compile current directory for a particular operating system:

`gox -os="{{os}}"`

- Compile current directory for a single operating system and architecture combination:

`gox -osarch="{{os}}/{{arch}}"`

