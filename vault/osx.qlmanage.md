---
id: osx.qlmanage
title: Qlmanage
desc: ''
updated: 1615663978760
created: 1615663978760
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qlmanage

> QuickLook server tool.

- Display QuickLook for one or multiple files:

`qlmanage -p {{filename}} {{filename2}}`

- Compute 300px wide PNG thumbnails of all JPEGs in the current directory and put them in a directory:

`qlmanage {{*.jpg}} -t -s {{300}} {{path/to/directory}}`

- Reset Quicklook:

`qlmanage -r`
