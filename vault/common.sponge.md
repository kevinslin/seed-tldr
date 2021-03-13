---
id: common.sponge
title: Sponge
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sponge

> Soak up the input before writing the output file.
> More information: <https://linux.die.net/man/1/sponge>.

- Append file content to the source file:

`cat {{path/to/file}} | sponge -a {{path/to/file}}`

- Remove all lines starting with # in a file:

`grep -v '^{{#}}' {{path/to/file}} | sponge {{path/to/file}}`

