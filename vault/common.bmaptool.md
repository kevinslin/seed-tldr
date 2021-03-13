---
id: common.bmaptool
title: Bmaptool
desc: ''
updated: 1615663978701
created: 1615663978701
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bmaptool

> Create or copy block maps intelligently (designed to be faster than `cp` or `dd`).
> More information: <https://source.tizen.org/documentation/reference/bmaptool>.

- Create a blockmap from image file:

`bmaptool create -o {{blockmap.bmap}} {{source.img}}`

- Copy an image file into sdb:

`bmaptool copy --bmap {{blockmap.bmap}} {{source.img}} {{/dev/sdb}}`

- Copy a compressed image file into sdb:

`bmaptool copy --bmap {{blockmap.bmap}} {{source.img.gz}} {{/dev/sdb}}`

- Copy an image file into sdb without using a blockmap:

`bmaptool copy --nobmap {{source.img}} {{/dev/sdb}}`

