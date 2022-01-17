---
id: osx.xcrun
title: Xcrun
desc: ''
updated: 1642441815124
created: 1642441815124
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xcrun

> Run or locate development tools and properties.
> More information: <https://www.unix.com/man-page/osx/1/xcrun/>.

- Find and run a tool from the active developer directory:

`xcrun {{tool}} {{arguments}}`

- Show verbose output:

`xcrun {{tool}} {{arguments}} --verbose`

- Find a tool for a given SDK:

`xcrun --sdk {{sdk_name}}`

- Find a tool for a given toolchain:

`xcrun --toolchain {{name}}`

- Display help:

`xcrun --help`

- Display version:

`xcrun --version`

