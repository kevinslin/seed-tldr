---
id: common.go-list
title: Go List
desc: ''
updated: 1623965016130
created: 1623965016130
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# go list

> List packages or modules.
> More information: <https://golang.org/cmd/go/#hdr-List_packages_or_modules>.

- List packages:

`go list ./...`

- List standard packages:

`go list std`

- List packages in json format:

`go list -json time net/http`

- List module dependencies and available updates:

`go list -m -u all`

