---
id: osx.wc
title: Wc
desc: ''
updated: 1644840636314
created: 1644840636314
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wc

> Count lines, words, or bytes.
> More information: <https://ss64.com/osx/wc.html>.

- Count lines in file:

`wc -l {{path/to/file}}`

- Count words in file:

`wc -w {{path/to/file}}`

- Count characters (bytes) in file:

`wc -c {{path/to/file}}`

- Count characters in file (taking multi-byte character sets into account):

`wc -m {{path/to/file}}`

- Use standard input to count lines, words and characters (bytes) in that order:

`{{find .}} | wc`

