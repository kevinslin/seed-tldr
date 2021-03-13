---
id: linux.a2ensite
title: A2ensite
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# a2ensite

> Enable an Apache virtual host on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2ensite.8.en.html>.

- Enable a virtual host:

`sudo a2ensite {{virtual_host}}`

- Don't show informative messages:

`sudo a2ensite --quiet {{virtual_host}}`

