---
id: linux.tic
title: Tic
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tic

> Compile terminfo and install for ncurses.
> More information: <https://pubs.opengroup.org/onlinepubs/007908799/xcurses/terminfo.html>.

- Compile and install terminfo for a terminal:

`tic -xe {{terminal}} {{path/to/terminal.info}}`

- Check terminfo file for errors:

`tic -c {{path/to/terminal.info}}`

- Print database locations:

`tic -D`

