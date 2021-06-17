---
id: common.paste
title: Paste
desc: ''
updated: 1623965016141
created: 1623965016141
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# paste

> Merge lines of files.
> More information: <https://www.gnu.org/software/coreutils/paste>.

- Join all the lines into a single line, using TAB as delimiter:

`paste -s {{file}}`

- Join all the lines into a single line, using the specified delimiter:

`paste -s -d {{delimiter}} {{file}}`

- Merge two files side by side, each in its column, using TAB as delimiter:

`paste {{file1}} {{file2}}`

- Merge two files side by side, each in its column, using the specified delimiter:

`paste -d {{delimiter}} {{file1}} {{file2}}`

- Merge two files, with lines added alternatively:

`paste -d '\n' {{file1}} {{file2}}`

