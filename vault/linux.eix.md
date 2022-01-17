---
id: linux.eix
title: Eix
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eix

> Utilities for searching local Gentoo packages.
> Update local package cache using `eix-update`.
> More information: <https://wiki.gentoo.org/wiki/Eix>.

- Search for a package:

`eix {{package_name}}`

- Search for installed packages:

`eix --installed {{package_name}}`

- Search in package descriptions:

`eix --description "{{description}}"`

- Search by package license:

`eix --license {{license}}`

- Exclude results from search:

`eix --not --license {{license}}`

