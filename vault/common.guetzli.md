---
id: common.guetzli
title: Guetzli
desc: ''
updated: 1623965306191
created: 1623965306191
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# guetzli

> JPEG image compression utility.
> More information: <https://github.com/google/guetzli>.

- Compress a JPEG image:

`guetzli {{input.jpg}} {{output.jpg}}`

- Create compressed JPEG image from PNG image:

`guetzli {{input.png}} {{output.jpg}}`

- Compress a JPEG image with desired visual quality (84-100):

`guetzli --quality {{quality_value}} {{input.jpg}} {{output.jpg}}`

