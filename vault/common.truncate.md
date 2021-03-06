---
id: common.truncate
title: Truncate
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# truncate

> Shrink or extend the size of a file to the specified size.
> More information: <https://www.gnu.org/software/coreutils/truncate>.

- Set a size of 10 GB to an existing file, or create a new file with the specified size:

`truncate --size {{10G}} {{filename}}`

- Extend the file size by 50M, fill with holes (which reads as zero bytes):

`truncate --size +{{50M}} {{filename}}`

- Shrink the file by 2GiB, by removing data from the end of file:

`truncate --size -{{2G}} {{filename}}`

- Empty the file's content:

`truncate --size 0 {{filename}}`

- Empty the file's content, but do not create the file if it does not exist:

`truncate --no-create --size 0 {{filename}}`

