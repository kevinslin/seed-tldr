---
id: common.carp
title: Carp
desc: ''
updated: 1642441815001
created: 1642441815001
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# carp

> REPL and build tool for Carp.
> More information: <https://carp-lang.github.io/carp-docs/Manual.html>.

- Start a REPL (interactive shell):

`carp`

- Start a REPL with a custom prompt:

`carp --prompt "{{> }}"`

- Build a `carp` file:

`carp -b {{path/to/file.carp}}`

- Build and run a file:

`carp -x {{path/to/file.carp}}`

- Build a file with optimizations enabled:

`carp -b --optimize {{path/to/file.carp}}`

- Transpile a file to C code:

`carp --generate-only {{path/to/file.carp}}`

