---
id: common.gnuplot
title: Gnuplot
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnuplot

> A graph plotter that outputs in several formats.
> More information: <http://www.gnuplot.info/>.

- Start the interactive graph plotting shell:

`gnuplot`

- Plot the graph for the specified graph definition file:

`gnuplot {{path/to/definition.plt}}`

- Set the output format by executing a command before loading the definition file:

`gnuplot -e "{{set output "path/to/filename.png" size 1024,768}}" {{path/to/definition.plt}}`

- Persist the graph plot preview window after gnuplot exits:

`gnuplot --persist {{path/to/definition.plt}}`

