---
id: linux.a2enmod
title: A2enmod
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# a2enmod

> Enable an Apache module on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2enmod.8.en.html>.

- Enable a module:

`sudo a2enmod {{module}}`

- Don't show informative messages:

`sudo a2enmod --quiet {{module}}`

