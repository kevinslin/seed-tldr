---
id: common.zopflipng
title: Zopflipng
desc: ''
updated: 1623965306217
created: 1623965306217
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zopflipng

> PNG image compression utility.
> More information: <https://github.com/google/zopfli>.

- Optimize a PNG image:

`zopflipng {{input.png}} {{output.png}}`

- Optimize several PNG images and save with given prefix:

`zopflipng --prefix={{prefix}} {{image1.png}} {{image2.png}} {{image3.png}}`

