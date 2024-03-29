---
id: common.stl2gts
title: Stl2gts
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stl2gts

> Convert STL files into the GTS (GNU triangulated surface library) file format.
> More information: <https://manned.org/stl2gts>.

- Convert an STL file to a GTS file:

`stl2gts < {{path/to/file.stl}} > {{path/to/file.gts}}`

- Convert an STL file to a GTS file and revert face normals:

`stl2gts --revert < {{path/to/file.stl}} > {{path/to/file.gts}}`

- Convert an STL file to a GTS file and do not merge vertices:

`stl2gts --nomerge < {{path/to/file.stl}} > {{path/to/file.gts}}`

- Convert an STL file to a GTS file and display surface statistics:

`stl2gts --verbose < {{path/to/file.stl}} > {{path/to/file.gts}}`

- Print help for `stl2gts`:

`stl2gts --help`

