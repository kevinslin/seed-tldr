---
id: common.go-env
title: Go Env
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
# go env

> Manage environment variables used by the Go toolchain.
> More information: <https://golang.org/cmd/go/#hdr-Print_Go_environment_information>.

- Show all environment variables:

`go env`

- Show a specific environment variable:

`go env {{GOPATH}}`

- Set an environment variable to a value:

`go env -w {{GOBIN}}={{path/to/directory}}`

- Reset an environment variable's value:

`go env -u {{GOBIN}}`

