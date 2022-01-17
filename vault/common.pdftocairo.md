---
id: common.pdftocairo
title: Pdftocairo
desc: ''
updated: 1642441815056
created: 1642441815056
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdftocairo

> Converts PDF files to PNG/JPEG/TIFF/PDF/PS/EPS/SVG using cairo.
> More information: <https://poppler.freedesktop.org>.

- Convert a PDF file to JPEG:

`pdftocairo {{path/to/file.pdf}} -jpeg`

- Convert to PDF expanding the output to fill the paper:

`pdftocairo {{path/to/file.pdf}} {{output.pdf}} -pdf -expand`

- Convert to SVG specifying the first/last page to convert:

`pdftocairo {{path/to/file.pdf}} {{output.svg}} -svg -f {{first_page}} -l {{last_page}}`

- Convert to PNG with 200ppi resolution:

`pdftocairo {{path/to/file.pdf}} {{output.png}} -png -r 200`

- Convert to grayscale TIFF setting paper size to A3:

`pdftocairo {{path/to/file.pdf}} -tiff -gray -paper A3`

- Convert to PNG cropping x and y pixels from the top-left corner:

`pdftocairo {{path/to/file.pdf}} -png -x {{x_pixels}} -y {{y_pixels}}`

