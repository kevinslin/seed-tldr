---
id: osx.port
title: Port
desc: ''
updated: 1644811682010
created: 1644811682010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# port

> Package manager for macOS.
> More information: <https://www.macports.org>.

- Search for a package:

`port search {{search_term}}`

- Install a package:

`sudo port install {{package_name}}`

- List installed packages:

`port installed`

- Update port and fetch the latest list of available packages:

`sudo port selfupdate`

- Upgrade outdated packages:

`sudo port upgrade outdated`

- Remove old versions of installed packages:

`sudo port uninstall inactive`

