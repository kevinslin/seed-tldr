---
id: osx.lipo
title: Lipo
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lipo

> Tool for handling Mach-O Universal Binaries.
> More information: <https://ss64.com/osx/lipo.html>.

- Create a universal file from two single-architecture files:

`lipo {{path/to/binary.x86_64}} {{path/to/binary.arm64e}} -create -output {{path/to/binary}}`

- List all architectures contained in a universal file:

`lipo {{path/to/binary}} -archs`

- Display detailed information about a universal file:

`lipo {{path/to/binary}} -detailed_info`

- Extract a single-architecture file from a universal file:

`lipo {{path/to/binary}} -thin {{arm64e}} -output {{path/to/binary.arm64e}}`

