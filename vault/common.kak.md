---
id: common.kak
title: Kak
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kak

> Kakoune is a mode-based code editor implementing the "multiple selections" paradigm.
> Data can be selected and simultaneously edited in different locations, using multiple selections; users can also connect to the same session for collaborative editing.
> More information: <https://kakoune.org>.

- Open a file and enter normal mode, to execute commands:

`kak {{path/to/file}}`

- Enter insert mode from normal mode, to write text into the file:

`i`

- Escape insert mode, to go back to normal mode:

`<Escape>`

- Replace all instances of "foo" in the current file with "bar":

`%s{{foo}}<Enter>c{{bar}}<Escape>`

- Un-select all secondary selections, and keep only the main one:

`<Space>`

- Search for numbers and select the first two:

`/\d+<Enter>N`

- Insert the contents of a file:

`!cat {{path/to/file}}<Enter>`

- Save the current file:

`:w<Enter>`

