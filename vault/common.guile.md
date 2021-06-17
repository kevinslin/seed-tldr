---
id: common.guile
title: Guile
desc: ''
updated: 1623965306191
created: 1623965306191
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# guile

> Guile Scheme interpreter.
> More information: <https://www.gnu.org/software/guile>.

- Start the Guile Scheme REPL:

`guile`

- Execute the script in a given Scheme file:

`guile {{script.scm}}`

- Execute a Scheme expression:

`guile -c "{{expression}}"`

- Listen on a port or a Unix domain socket (the default is port 37146) for remote REPL connections:

`guile --listen={{port_or_socket}}`

