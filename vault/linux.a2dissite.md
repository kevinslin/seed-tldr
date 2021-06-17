---
id: linux.a2dissite
title: A2dissite
desc: ''
updated: 1623965016157
created: 1623965016157
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# a2dissite

> Disable an Apache virtual host on Debian-based OSes.
> More information: <https://manpages.debian.org/latest/apache2/a2dissite.8.en.html>.

- Disable a virtual host:

`sudo a2dissite {{virtual_host}}`

- Don't show informative messages:

`sudo a2dissite --quiet {{virtual_host}}`

