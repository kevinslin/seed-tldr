---
id: linux.avifenc
title: Avifenc
desc: ''
updated: 1642574149063
created: 1642574149063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# avifenc

> AV1 Image File Format (AVIF) encoder.
> More information: <https://aomediacodec.github.io/av1-avif/>.

- Convert a specific PNG image to AVIF:

`avifenc {{path/to/image.png}} {{path/to/image.avif}}`

- Encode with a specific speed, where 0=slowest, 10=fastest, and 6=default:

`avifenc --speed {{2}} {{path/to/image.png}} {{path/to/image.avif}}`

