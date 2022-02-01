---
id: common.openscad
title: Openscad
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
# openscad

> Software for creating solid 3D CAD objects.
> More information: <https://openscad.org>.

- Open a file:

`openscad {{path/to/button.scad}}`

- Convert a file to STL:

`openscad -o {{path/to/button.stl}} {{path/to/button.scad}}`

- Render a file to PNG in a specific colorscheme:

`openscad -o {{path/to/button.png}} --colorscheme {{Sunset}} {{path/to/button.scad}}`

