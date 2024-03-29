---
id: common.okular
title: Okular
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# okular

> A universal document viewer.
> More information: <https://okular.kde.org/>.

- Launch Okular:

`okular`

- Open specific documents in Okular:

`okular {{path/to/file1 path/to/file2 ...}}`

- Open a document at a specific page:

`okular --page {{page_number}} {{path/to/file}}`

- Open a document in presentation mode:

`okular --presentation {{path/to/file}}`

- Open a document and start the print dialog:

`okular --print {{path/to/file}}`

- Open a document and search for a specific string:

`okular --find {{search_string}} {{path/to/file}}`

