---
id: linux.apt-cache
title: Apt Cache
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-cache

> Debian and Ubuntu package query tool.
> More information: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Search for a package in your current sources:

`apt-cache search {{query}}`

- Show information about a package:

`apt-cache show {{package}}`

- Show whether a package is installed and up to date:

`apt-cache policy {{package}}`

- Show dependencies for a package:

`apt-cache depends {{package}}`

- Show packages that depend on a particular package:

`apt-cache rdepends {{package}}`

