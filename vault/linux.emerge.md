---
id: linux.emerge
title: Emerge
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# emerge

> Gentoo Linux package manager utility.

- Synchronize all packages:

`emerge --sync`

- Update all packages, including dependencies:

`emerge -uDNav @world`

- Resume a failed updated, skipping the failing package:

`emerge --resume --skipfirst`

- Install a new package, with confirmation:

`emerge -av {{package_name}}`

- Remove a package, with confirmation:

`emerge -Cav {{package_name}}`

- Remove orphaned packages (that were installed only as dependencies):

`emerge -avc`

- Search the package database for a keyword:

`emerge -S {{keyword}}`

