---
id: linux.libreoffice
title: Libreoffice
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# libreoffice

> CLI for the powerful and free office suite LibreOffice.
> More information: <https://www.libreoffice.org/>.

- Open a space-separated list of files in read-only mode:

`libreoffice --view {{path/to/file1}} {{path/to/file2}}`

- Display the content of specific files:

`libreoffice --cat {{path/to/file1}} {{path/to/file2}}`

- Print files to a specific printer:

`libreoffice --pt {{printer_name}} {{path/to/file1}} {{path/to/file2}}`

- Convert all `.doc` files in current directory to PDF:

`libreoffice --convert-to {{pdf}} {{*.doc}}`

