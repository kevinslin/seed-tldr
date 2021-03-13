---
id: common.pdfimages
title: Pdfimages
desc: ''
updated: 1615655543077
created: 1615655543077
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

