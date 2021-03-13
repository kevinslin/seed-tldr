---
id: common.go-build
title: Go Build
desc: ''
updated: 1615663978715
created: 1615663978715
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# go build

> Compile Go sources.
> More information: <https://golang.org/cmd/go/#hdr-Compile_packages_and_dependencies>.

- Compile a file:

`go build {{path/to/main.go}}`

- Compile, specifying the output filename:

`go build -o {{path/to/binary}} {{path/to/source.go}}`

- Compile a package:

`go build -o {{path/to/binary}} {{path/to/package}}`

- Compile a main package into an executable, with data race detection:

`go build -race -o {{path/to/executable}} {{path/to/main/package}}`
