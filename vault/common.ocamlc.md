---
id: common.ocamlc
title: Ocamlc
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

