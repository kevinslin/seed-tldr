---
id: common.dune
title: Dune
desc: ''
updated: 1642441815011
created: 1642441815011
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dune

> A build system for OCaml programs.
> More information: <https://dune.build>.

- Build all targets:

`dune build`

- Clean up the workspace:

`dune clean`

- Run all tests:

`dune runtest`

- Start the utop REPL with compiled modules automatically loaded into it, to remove the need to load them by hand:

`dune utop`

