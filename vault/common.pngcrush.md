---
id: common.pngcrush
title: Pngcrush
desc: ''
updated: 1642441815060
created: 1642441815060
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pngcrush

> PNG compression utility.
> More information: <https://pmt.sourceforge.io/pngcrush>.

- Compress a PNG file:

`pngcrush {{in.png}} {{out.png}}`

- Compress all PNGs and output them to the specified directory:

`pngcrush -d {{path/to/output}} *.png`

- Compress PNG file with all 114 available algorithms and pick the best result:

`pngcrush -rem allb -brute -reduce {{in.png}} {{out.png}}`

