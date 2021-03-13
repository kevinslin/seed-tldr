---
id: common.vim
title: Vim
desc: ''
updated: 1615663978738
created: 1615663978738
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vim

> Vim (Vi IMproved), a command-line text editor, provides several modes for different kinds of text manipulation.
> Pressing `i` enters edit mode. `<Esc>` goes back to normal mode, which doesn't allow regular text insertion.
> More information: <https://www.vim.org>.

- Open a file:

`vim {{path/to/file}}`

- View Vim's help manual:

`:help<Enter>`

- Save and Quit:

`:wq<Enter>`

- Open a file at a specified line number:

`vim +{{line_number}} {{path/to/file}}`

- Undo the last operation:

`u`

- Search for a pattern in the file (press `n`/`N` to go to next/previous match):

`/{{search_pattern}}<Enter>`

- Perform a regex substitution in the whole file:

`:%s/{{pattern}}/{{replacement}}/g<Enter>`

- Display the line numbers:

`:set nu<Enter>`

