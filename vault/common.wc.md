---
id: common.wc
title: Wc
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wc

> Count lines, words, or bytes.
> More information: <https://www.gnu.org/software/coreutils/wc>.

- Count lines in file:

`wc -l {{file}}`

- Count words in file:

`wc -w {{file}}`

- Count characters (bytes) in file:

`wc -c {{file}}`

- Count characters in file (taking multi-byte character sets into account):

`wc -m {{file}}`

- Use standard input to count lines, words and characters (bytes) in that order:

`{{find .}} | wc`

