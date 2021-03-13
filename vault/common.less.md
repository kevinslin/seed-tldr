---
id: common.less
title: Less
desc: ''
updated: 1615663978722
created: 1615663978722
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# less

> Open a file for interactive reading, allowing scrolling and search.

- Open a file:

`less {{source_file}}`

- Page down / up:

`<Space> (down), b (up)`

- Go to end / start of file:

`G (end), g (start)`

- Forward search for a string (press `n`/`N` to go to next/previous match):

`/{{something}}`

- Backward search for a string (press `n`/`N` to go to next/previous match):

`?{{something}}`

- Follow the output of the currently opened file:

`F`

- Open the current file in an editor:

`v`

- Exit:

`q`
