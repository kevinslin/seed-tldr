---
id: common.fmt
title: Fmt
desc: ''
updated: 1615663978709
created: 1615663978709
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fmt

> Reformat a text file by joining its paragraphs and limiting the line width to given number of characters (75 by default).

- Reformat a file:

`fmt {{path/to/file}}`

- Reformat a file producing output lines of (at most) `n` characters:

`fmt -w {{n}} {{path/to/file}}`

- Reformat a file without joining lines shorter than the given width together:

`fmt -s {{path/to/file}}`

- Reformat a file with uniform spacing (1 space between words and 2 spaces between paragraphs):

`fmt -u {{path/to/file}}`

