---
id: linux.dpkg-deb
title: Dpkg Deb
desc: ''
updated: 1623965306221
created: 1623965306221
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dpkg-deb

> Pack, unpack and provide information about Debian archives.
> More information: <https://manpages.debian.org/buster/dpkg/dpkg-deb.1.en.html>.

- Display information about a package:

`dpkg-deb --info {{path/to/file.deb}}`

- Display the package's name and version on one line:

`dpkg-deb --show {{path/to/file.deb}}`

- List the package's contents:

`dpkg-deb --contents {{path/to/file.deb}}`

- Extract package's contents into a directory:

`dpkg-deb --extract {{path/to/file.deb}} {{path/to/directory}}`

- Create a package from a specified directory:

`dpkg-deb --build {{path/to/directory}}`

