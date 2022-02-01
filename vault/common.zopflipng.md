---
id: common.zopflipng
title: Zopflipng
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zopflipng

> PNG compression utility.
> More information: <https://github.com/google/zopfli>.

- Optimize a PNG:

`zopflipng {{input.png}} {{output.png}}`

- Optimize several PNGs and save with given prefix:

`zopflipng --prefix={{prefix}} {{image1.png}} {{image2.png}} {{image3.png}}`

