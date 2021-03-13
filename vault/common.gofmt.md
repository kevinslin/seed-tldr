---
id: common.gofmt
title: Gofmt
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

