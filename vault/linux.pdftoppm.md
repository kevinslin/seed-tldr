---
id: linux.pdftoppm
title: Pdftoppm
desc: ''
updated: 1644591952806
created: 1644591952806
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdftoppm

> Convert PDF document pages to portable Pixmap (image formats).
> More information: <https://manned.org/pdftoppm>.

- Specify the range of pages to convert (N-first page, M-last page):

`pdftoppm -f {{N}} -l {{M}} {{path/to/file.pdf}} {{image_name_prefix}}`

- Convert only the first page of a PDF:

`pdftoppm -singlefile {{path/to/file.pdf}} {{image_name_prefix}}`

- Generate a monochrome PBM file (instead of a color PPM file):

`pdftoppm -mono {{path/to/file.pdf}} {{image_name_prefix}}`

- Generate a grayscale PGM file (instead of a color PPM file):

`pdftoppm -gray {{path/to/file.pdf}} {{image_name_prefix}}`

- Generate a PNG file instead a PPM file:

`pdftoppm -png {{path/to/file.pdf}} {{image_name_prefix}}`

