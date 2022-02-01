---
id: common.unflatten
title: Unflatten
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unflatten

> Adjust directed graphs to improve the layout aspect ratio.
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.
> More information: <https://www.graphviz.org/pdf/unflatten.1.pdf>.

- Adjust one or more directed graphs to improve the layout aspect ratio:

`unflatten {{path/to/input1.gv}} {{path/to/input2.gv ...}} > {{path/to/output.gv}}`

- Use `unflatten` as a preprocessor for `dot` layout to improve aspect ratio:

`unflatten {{path/to/input.gv}} | dot -T {{png}} {{path/to/output.png}}`

- Display help for `unflatten`:

`unflatten -?`

