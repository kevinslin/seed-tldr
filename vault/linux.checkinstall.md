---
id: linux.checkinstall
title: Checkinstall
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# checkinstall

> Track the local installation of a software package, and produce a binary package which can be used with a system's native package manager.
> More information: <http://checkinstall.izto.org>.

- Create and install a package with default settings:

`sudo checkinstall --default`

- Create a package but don't install it:

`sudo checkinstall --install={{no}}`

- Create a package without documentation:

`sudo checkinstall --nodoc`

- Create a package and set the name:

`sudo checkinstall --pkgname {{package}}`

- Create a package and specify where to save it:

`sudo checkinstall --pakdir {{path/to/directory}}`

