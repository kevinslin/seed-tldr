---
id: osx.qlmanage
title: Qlmanage
desc: ''
updated: 1644840636311
created: 1644840636311
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qlmanage

> QuickLook server tool.
> More information: <https://ss64.com/osx/qlmanage.html>.

- Display QuickLook for one or multiple files:

`qlmanage -p {{filename}} {{filename2}}`

- Compute 300px wide PNG thumbnails of all JPEGs in the current directory and put them in a directory:

`qlmanage {{*.jpg}} -t -s {{300}} {{path/to/directory}}`

- Reset QuickLook:

`qlmanage -r`

