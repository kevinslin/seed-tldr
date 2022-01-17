---
id: common.sccmap
title: Sccmap
desc: ''
updated: 1642441815067
created: 1642441815067
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sccmap

> Extract strongly connected components of directed graphs.
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.
> More information: <https://www.graphviz.org/pdf/sccmap.1.pdf>.

- Extract strongly connected components of one or more directed graphs:

`sccmap -S {{path/to/input1.gv}} {{path/to/input2.gv ...}} > {{path/to/output.gv}}`

- Print statistics about a graph, producing no output graph:

`sccmap -v -s {{path/to/input1.gv}} {{path/to/input2.gv ...}}`

- Display help for `sccmap`:

`sccmap -?`

