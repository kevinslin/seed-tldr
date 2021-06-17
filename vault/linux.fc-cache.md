---
id: linux.fc-cache
title: Fc Cache
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
# fc-cache

> Scan font directories in order to build font cache files.

- Generate font cache files:

`fc-cache`

- Force a rebuild of all font cache files, without checking if cache is up-to-date:

`fc-cache -f`

- Erase font cache files, then generate new font cache files:

`fc-cache -r`

