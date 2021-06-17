---
id: linux.phpenmod
title: Phpenmod
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
# phpenmod

> Enable PHP extensions on Debian-based OSes.

- Enable the json extension for every SAPI of every PHP version:

`sudo phpenmod {{json}}`

- Enable the json extension for PHP 7.3 with the cli SAPI:

`sudo phpenmod -v {{7.3}} -s {{cli}} {{json}}`

