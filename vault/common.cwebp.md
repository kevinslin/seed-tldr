---
id: common.cwebp
title: Cwebp
desc: ''
updated: 1643706415070
created: 1643706415070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cwebp

> Compress an image file to a WebP file.
> More information: <https://developers.google.com/speed/webp/docs/cwebp>.

- Compress a WebP file with default settings (q = 75) to the [o]utput file:

`cwebp {{path/to/image_file}} -o {{path/to/output.webp}}`

- Compress a WebP file with the best [q]uality and largest file size:

`cwebp {{path/to/image_file}} -o {{path/to/output.webp}} -q {{100}}`

- Compress a WebP file with the worst [q]uality and smallest file size:

`cwebp {{path/to/image_file}} -o {{path/to/output.webp}} -q {{0}}`

- Compress a WebP file and apply resize to image:

`cwebp {{path/to/image_file}} -o {{path/to/output.webp}} -resize {{width}} {{height}}`

- Compress a WebP file and drop alpha channel information:

`cwebp {{path/to/image_file}} -o {{path/to/output.webp}} -noalpha`

