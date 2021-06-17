---
id: common.ocamlc
title: Ocamlc
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ocamlc

> The OCaml bytecode compiler.
> Produces executables runnable by the OCaml interpreter.
> More information: <https://ocaml.org>.

- Create a binary from a source file:

`ocamlc {{path/to/source_file.ml}}`

- Create a named binary from a source file:

`ocamlc -o {{path/to/binary}} {{path/to/source_file.ml}}`

- Automatically generate a module signature (interface) file:

`ocamlc -i {{path/to/source_file.ml}}`

