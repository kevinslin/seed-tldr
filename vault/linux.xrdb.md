---
id: linux.xrdb
title: Xrdb
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xrdb

> X window server's resource database utility for Unix-like systems.
> More information: <https://www.x.org/releases/X11R7.7/doc/man/man1/xrdb.1.xhtml>.

- Start `xrdb` in interactive mode:

`xrdb`

- Load values (e.g. style rules) from a resource file:

`xrdb -load {{~/.Xresources}}`

- Query the resource database and print currently set values:

`xrdb -query`

