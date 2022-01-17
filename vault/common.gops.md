---
id: common.gops
title: Gops
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
# gops

> CLI tool which lists and diagnoses Go processes currently running on your system.
> More information: <https://github.com/google/gops>.

- Print all go processes running locally:

`gops`

- Print more information about a process:

`gops {{pid}}`

- Display a process tree:

`gops tree`

- Print the current stack trace from a target program:

`gops stack {{pid|addr}}`

- Print the current runtime memory statistics:

`gops memstats {{pid|addr}}`

