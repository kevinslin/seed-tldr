---
id: common.sponge
title: Sponge
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sponge

> Soak up the input before writing the output file.
> More information: <https://manned.org/sponge>.

- Append file content to the source file:

`cat {{path/to/file}} | sponge -a {{path/to/file}}`

- Remove all lines starting with # in a file:

`grep -v '^{{#}}' {{path/to/file}} | sponge {{path/to/file}}`

