---
id: common.acyclic
title: Acyclic
desc: ''
updated: 1642441814992
created: 1642441814992
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# acyclic

> Make a directed graph acyclic by reversing some edges.
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.
> More information: <https://graphviz.org/pdf/acyclic.1.pdf>.

- Make a directed graph acyclic by reversing some edges:

`acyclic {{path/to/input.gv}} > {{path/to/output.gv}}`

- Print if a graph is acyclic, has a cycle, or is undirected, producing no output graph:

`acyclic -v -n {{path/to/input.gv}}`

- Display help for `acyclic`:

`acyclic -?`

