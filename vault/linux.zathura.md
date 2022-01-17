---
id: linux.zathura
title: Zathura
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
# zathura

> A vim-like modal document viewer, with an integrated command line.
> Make sure a backend is installed (poppler, PostScript, or DjVu).
> More information: <https://pwmt.org/projects/zathura/>.

- Open a file:

`zathura {{path/to/file}}`

- Navigate left/up/down/right:

`<H|J|K|L> or arrow keys`

- Rotate:

`r`

- Invert Colors:

`Ctrl + R`

- Search for text by a given string:

`/{{string}}`

- Create/delete bookmarks:

`:{{bmark|bdelete}} {{bookmark_name}}`

- List bookmarks:

`:blist`

