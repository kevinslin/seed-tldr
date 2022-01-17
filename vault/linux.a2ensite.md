---
id: linux.a2ensite
title: A2ensite
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# a2ensite

> Enable an Apache virtual host on Debian-based OSes.
> More information: <https://manpages.debian.org/latest/apache2/a2ensite.8.en.html>.

- Enable a virtual host:

`sudo a2ensite {{virtual_host}}`

- Don't show informative messages:

`sudo a2ensite --quiet {{virtual_host}}`

