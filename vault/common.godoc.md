---
id: common.godoc
title: Godoc
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# godoc

> Show documentation for go packages.
> More information: <https://godoc.org/>.

- Display help for package "fmt":

`godoc {{fmt}}`

- Display help for the function "Printf" of "fmt" package:

`godoc {{fmt}} {{Printf}}`

- Serve documentation as a web server on port 6060:

`godoc -http=:{{6060}}`

- Create an index file:

`godoc -write_index -index_files={{path/to/file}}`

- Use the given index file to search the docs:

`godoc -http=:{{6060}} -index -index_files={{path/to/file}}`

