---
id: common.fold
title: Fold
desc: ''
updated: 1623965306184
created: 1623965306184
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fold

> Wraps each line in an input file to fit a specified width and prints it to the standard output.
> More information: <https://www.gnu.org/software/coreutils/fold>.

- Wrap each line to default width (80 characters):

`fold {{file}}`

- Wrap each line to width "30":

`fold -w30 {{file}}`

- Wrap each line to width "5" and break the line at spaces (puts each space separated word in a new line, words with length > 5 are wrapped):

`fold -w5 -s {{file}}`

