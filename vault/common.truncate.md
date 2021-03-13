---
id: common.truncate
title: Truncate
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# truncate

> Shrink or extend the size of a file to the specified size.

- Set a size of 10 GB to an exsting file, or create a new file with the specified size:

`truncate -s {{10G}} {{filename}}`

- Extend the file size by 50M, fill with holes (which reads as zero bytes):

`truncate -s +{{50M}} {{filename}}`

- Shrink the file by 2GiB, by removing data from the end of file:

`truncate -s -{{2G}} {{filename}}`

- Empty the file's content:

`truncate -s 0 {{filename}}`

