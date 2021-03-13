---
id: linux.phpdismod
title: Phpdismod
desc: ''
updated: 1615663978752
created: 1615663978752
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpdismod

> Disable PHP extensions on Debian-based OSes.

- Disable the json extension for every SAPI of every PHP version:

`sudo phpdismod {{json}}`

- Disable the json extension for PHP 7.3 with the cli SAPI:

`sudo phpdismod -v {{7.3}} -s {{cli}} {{json}}`

