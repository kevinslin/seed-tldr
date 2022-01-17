---
id: common.most
title: Most
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# most

> Open one or several files for interactive reading, allowing scrolling and search.
> More information: <https://manned.org/most>.

- Open a file:

`most {{path/to/file}}`

- Open several files:

`most {{path/to/file1}} {{path/to/file2}}`

- Open a file at the first occurrence of "string":

`most {{file}} +/{{string}}`

- Move through opened files:

`:O n`

- Jump to the 100th line:

`{{100}}j`

- Edit current file:

`e`

- Split the current window in half:

`<CTRL-x> o`

- Exit:

`Q`

