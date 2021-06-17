---
id: common.qr
title: Qr
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
# qr

> Generate QR codes in the terminal with ANSI VT-100 escape codes.
> More information: <https://github.com/lincolnloop/python-qrcode/>.

- Generate a QR code:

`echo "{{data}}" | qr`

- Specify the error correction level (defaults to M):

`echo "{{data}}" | qr --error-correction={{L|M|Q|H}}`

