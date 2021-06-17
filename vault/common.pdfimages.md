---
id: common.pdfimages
title: Pdfimages
desc: ''
updated: 1623965306202
created: 1623965306202
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfimages

> Utility for extracting images from PDFs.

- Extract all images from a PDF file and save them as PNGs:

`pdfimages -png {{path/to/file.pdf}} {{filename_prefix}}`

- Extract images from pages 3 to 5:

`pdfimages -f {{3}} -l {{5}} {{path/to/file.pdf}} {{filename_prefix}}`

- Extract images from a PDF file and include the page number in the output filenames:

`pdfimages -p {{path/to/file.pdf}} {{filename_prefix}}`

- List information about all the images in a PDF file:

`pdfimages -list {{path/to/file.pdf}}`

