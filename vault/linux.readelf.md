---
id: linux.readelf
title: Readelf
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# readelf

> Displays information about ELF files.
> More information: <http://man7.org/linux/man-pages/man1/readelf.1.html>.

- Display all information about the ELF file:

`readelf -all {{path/to/binary}}`

- Display all the headers present in the ELF file:

`readelf --headers {{path/to/binary}}`

- Display the entries in symbol table section of the ELF file, if it has one:

`readelf --symbols {{path/to/binary}}`

- Display the information contained in the ELF header at the start of the file:

`readelf --file-header {{path/to/binary}}`

