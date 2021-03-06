---
id: linux.phpquery
title: Phpquery
desc: ''
updated: 1623965306227
created: 1623965306227
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpquery

> PHP extension manager for Debian-based OSes.

- List available PHP versions:

`sudo phpquery -V`

- List available SAPIs for PHP 7.3:

`sudo phpquery -v {{7.3}} -S`

- List enabled extensions for PHP 7.3 with the cli SAPI:

`sudo phpquery -v {{7.3}} -s {{cli}} -M`

- Check if the json extension is enabled for PHP 7.3 with the apache2 SAPI:

`sudo phpquery -v {{7.3}} -s {{apache2}} -m {{json}}`

