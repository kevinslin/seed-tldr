---
id: common.ocamlopt
title: Ocamlopt
desc: ''
updated: 1623965016140
created: 1623965016140
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ocamlopt

> The OCaml native code compiler.
> Produces native executables, e.g. ELF on Linux.
> More information: <https://ocaml.org>.

- Compile a source file:

`ocamlopt -o {{path/to/binary}} {{path/to/source_file.ml}}`

- Compile with debugging enabled:

`ocamlopt -g -o {{path/to/binary}} {{path/to/source_file.ml}}`

