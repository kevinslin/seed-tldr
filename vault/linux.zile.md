---
id: linux.zile
title: Zile
desc: ''
updated: 1642441815119
created: 1642441815119
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zile

> Zile is a lightweight clone of the Emacs text editor.
> More information: <https://www.gnu.org/software/zile/>.

- Start a buffer for temporary notes, which won't be saved:

`zile`

- Open a file:

`zile {{path/to/file}}`

- Save a file:

`Ctrl + X, Ctrl + S`

- Quit:

`Ctrl + X, Ctrl + C`

- Open a file at a specified line number:

`zile +{{line_number}} {{path/to/file}}`

- Undo changes:

`Ctrl + X, U`

