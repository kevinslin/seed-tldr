---
id: linux.tic
title: Tic
desc: ''
updated: 1615663978756
created: 1615663978756
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
