---
id: common.graphml2gv
title: Graphml2gv
desc: ''
updated: 1642441815031
created: 1642441815031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# graphml2gv

> Convert a graph from `graphml` to `gv` format.
> Converters: `gml2gv`, `gv2gml`, `gv2gxl`, `gxl2gv`, `graphml2gv` & `mm2gv`.
> More information: <https://graphviz.org/pdf/graphml2gv.1.pdf>.

- Convert a graph from `gml` to `gv` format:

`graphml2gv -o {{output.gv}} {{input.gml}}`

- Convert a graph using stdin and stdout:

`cat {{input.gml}} | graphml2gv > {{output.gv}}`

- Display help:

`graphml2gv -?`

