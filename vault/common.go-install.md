---
id: common.go-install
title: Go Install
desc: ''
updated: 1642441815029
created: 1642441815029
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# go install

> Compile and install packages named by the import paths.
> More information: <https://pkg.go.dev/cmd/go#hdr-Compile_and_install_packages_and_dependencies>.

- Compile and install the current package:

`go install`

- Compile and install a specific local package:

`go install {{path/to/package}}`

- Install the latest version of a program, ignoring `go.mod` in the current directory:

`go install {{golang.org/x/tools/gopls}}@{{latest}}`

- Install a program at the version selected by `go.mod` in the current directory:

`go install {{golang.org/x/tools/gopls}}`

