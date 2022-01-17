---
id: linux.phpdismod
title: Phpdismod
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpdismod

> Disable PHP extensions on Debian-based OSes.
> More information: <https://salsa.debian.org/php-team/php-defaults>.

- Disable the JSON extension for every SAPI of every PHP version:

`sudo phpdismod {{json}}`

- Disable the JSON extension for PHP 7.3 with the cli SAPI:

`sudo phpdismod -v {{7.3}} -s {{cli}} {{json}}`

