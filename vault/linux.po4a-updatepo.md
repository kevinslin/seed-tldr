---
id: linux.po4a-updatepo
title: Po4a Updatepo
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# po4a-updatepo

> Update the translation (in PO format) of a documentation.
> More information: <https://po4a.org/man/man1/po4a-updatepo.1.php>.

- Update a PO file according to the modification of its origin file:

`po4a-updatepo --format {{text}} --master {{path/to/master.txt}} --po {{path/to/result.po}}`

- Get a list of available formats:

`po4a-updatepo --help-format`

- Update several PO files according to the modification of their origin file:

`po4a-updatepo --format {{text}} --master {{path/to/master.txt}} --po {{path/to/po1.po}} --po {{path/to/po2.po}}`

