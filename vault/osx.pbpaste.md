---
id: osx.pbpaste
title: Pbpaste
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pbpaste

> Send the contents of the clipboard to standard output.

- Write the contents of the clipboard to a file:

`pbpaste > {{file}}`

- Use the contents of the clipboard as input to a command:

`pbpaste | grep foo`

