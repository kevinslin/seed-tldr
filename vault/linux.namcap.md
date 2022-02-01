---
id: linux.namcap
title: Namcap
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# namcap

> Check binary packages and source `PKGBUILD`s for common packaging mistakes.
> More information: <https://man.archlinux.org/man/namcap.1>.

- Check a specific `PKGBUILD` file:

`namcap {{path/to/pkgbuild}}`

- Check a specific package file:

`namcap {{path/to/package.pkg.tar.zst}}`

- Check a file, printing extra [i]nformational messages:

`namcap -i {{path/to/file}}`

