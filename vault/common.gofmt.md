---
id: common.gofmt
title: Gofmt
desc: ''
updated: 1615663978715
created: 1615663978715
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gofmt

> Tool for formatting Go source code.
> More information: <https://golang.org/cmd/gofmt/>.

- Format a file and display the result to the console:

`gofmt {{source.go}}`

- Format a file, overwriting the original file in-place:

`gofmt -w {{source.go}}`

- Format a file, and then simplify the code, overwriting the original file:

`gofmt -s -w {{source.go}}`

- Print all (including spurious) errors:

`gofmt -e {{source.go}}`

