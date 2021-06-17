---
id: common.qrencode
title: Qrencode
desc: ''
updated: 1623965306207
created: 1623965306207
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qrencode

> QR Code generator. Supports PNG and EPS.
> More information: <https://fukuchi.org/works/qrencode>.

- Convert a string to a QR code and save to an output file:

`qrencode -o {{path/to/output_file.png}} {{string}}`

- Convert an input file to a QR code and save to an output file:

`qrencode -o {{path/to/output_file.png}} -r {{path/to/input_file}}`

- Convert a string to a QR code and print it in terminal:

`qrencode -t ansiutf8 {{string}}`

- Convert input from pipe to a QR code and print it in terminal:

`echo {{string}} | qrencode -t ansiutf8`

