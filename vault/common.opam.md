---
id: common.opam
title: Opam
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# opam

> OCaml Package Manager.
> Manage OCaml compilers, tools and libraries.
> More information: <https://opam.ocaml.org/>.

- Initialize opam for first use:

`opam init`

- Search for packages:

`opam search {{package_name}}`

- Install a package and all of its dependencies:

`opam install {{package_name}}`

- Display detailed information about a package:

`opam show {{package_name}}`

- List all installed packages:

`opam list`

- Update the local package database:

`opam update`

- Upgrade all installed packages:

`opam upgrade`

- Display all commands:

`opam help`

