---
id: linux.kwrite
title: Kwrite
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kwrite

> Text editor of the KDE Desktop project.
> See also `kate`.
> More information: <https://apps.kde.org/kwrite/>.

- Open a text file:

`kwrite {{path/to/file}}`

- Open multiple text files:

`kwrite {{file1 file2 ...}}`

- Open a text file with a specific encoding:

`kwrite --encoding={{UTF-8}} {{path/to/file}}`

- Open a text file and navigate to a specific line and column:

`kwrite --line {{line_number}} --column {{column_number}} {{path/to/file}}`

