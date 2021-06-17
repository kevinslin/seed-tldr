---
id: linux.pkgfile
title: Pkgfile
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgfile

> Tool for searching files from packages in the official repositories on arch-based systems.
> See also `pacman files`, describing the usage of `pacman --files`.
> More information: <https://man.archlinux.org/man/extra/pkgfile/pkgfile.1>.

- Synchronize the pkgfile database:

`sudo pkgfile --update`

- Search for a package that owns a specific file:

`pkgfile {{filename}}`

- List all files provided by a package:

`pkgfile --list {{package_name}}`

- List only files provided by a package located within the `bin` or `sbin` directory:

`pkgfile --list --binaries {{package_name}}`

- Search for a package that owns a specific file using case insensitive matching:

`pkgfile --ignorecase {{filename}}`

- Search for a package that owns a specific file in the `bin` or `sbin` directory:

`pkgfile --binaries {{filename}}`

- Search for a package that owns a specific file, displaying the package version:

`pkgfile --verbose {{filename}}`

- Search for a package that owns a specific file in a specific repository:

`pkgfile --repo {{repository_name}} {{filename}}`

