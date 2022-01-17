---
id: common.ocamlfind
title: Ocamlfind
desc: ''
updated: 1642441815052
created: 1642441815052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ocamlfind

> The findlib package manager for OCaml.
> Simplifies linking executables with external libraries.
> More information: <http://projects.camlcity.org/projects/findlib.html>.

- Compile a source file to a native binary and link with packages:

`ocamlfind ocamlopt -package {{package1}},{{package2}} -linkpkg -o {{executable}} {{source_file.ml}}`

- Compile a source file to a bytecode binary and link with packages:

`ocamlfind ocamlc -package {{package1}},{{package2}} -linkpkg -o {{executable}} {{source_file.ml}}`

- Cross-compile for a different platform:

`ocamlfind -toolchain {{cross-toolchain}} ocamlopt -o {{executable}} {{source_file.ml}}`

