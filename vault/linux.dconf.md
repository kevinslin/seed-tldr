---
id: linux.dconf
title: Dconf
desc: ''
updated: 1623965306220
created: 1623965306220
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dconf

> Simple tool for manipulating dconf databases.
> See also `dconf write`.
> More information: <https://developer.gnome.org/dconf>.

- Print the value of a dconf path:

`dconf read {{/example/dconf/path}}`

- List contents of a dconf path:

`dconf list {{/example/dconf/path}}`

- Watch for dconf database changes in a path and subpaths:

`dconf watch {{/example/dconf/path}}`

