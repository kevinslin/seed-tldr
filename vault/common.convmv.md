---
id: common.convmv
title: Convmv
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# convmv

> Convert filenames (NOT file content) from one encoding to another.
> More information: <https://www.j3e.de/linux/convmv/man/>.

- Test filename encoding conversion (don't actually change the filename):

`convmv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- Convert filename encoding and rename the file to the new encoding:

`convmv -f {{from_encoding}} -t {{to_encoding}} --notest {{input_file}}`

