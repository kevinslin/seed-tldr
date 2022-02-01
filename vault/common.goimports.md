---
id: common.goimports
title: Goimports
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# goimports

> Updates Go import lines, adding missing ones and removing unreferenced ones.
> More information: <https://godoc.org/golang.org/x/tools/cmd/goimports>.

- Display the completed import source file:

`goimports {{file}}.go`

- Write the result back to the source file instead of the standard output:

`goimports -w {{file}}.go`

- Display diffs and write the result back to the source file:

`goimports -w -d {{file}}.go`

- Set the import prefix string after 3rd-party packages (comma-separated list):

`goimports -local {{path/to/package}} {{file}}.go`

