---
id: osx.pkgutil
title: Pkgutil
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgutil

> Query and manipulate Mac OS X Installer packages and receipts.

- List package IDs for all installed packages:

`pkgutil --pkgs`

- Verify cryptographic signatures of a package file:

`pkgutil --check-signature {{path/to/filename.pkg}}`

- List all the files for an installed package given its ID:

`pkgutil --files {{com.microsoft.Word}}`

- Extract the contents of a package file into a directory:

`pkgutil --expand-full {{path/to/filename.pkg}} {{path/to/directory}}`

