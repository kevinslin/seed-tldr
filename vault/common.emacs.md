---
id: common.emacs
title: Emacs
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# emacs

> The extensible, customizable, self-documenting, real-time display editor.
> More information: <https://www.gnu.org/software/emacs>.

- Start in console mode (without X window):

`emacs -nw`

- Open a file:

`emacs {{path/to/file}}`

- Save a file:

`Ctrl + X, Ctrl + S`

- Quit:

`Ctrl + X, Ctrl + C`

- Open a file at a specified line number:

`emacs +{{line_number}} {{path/to/file}}`

