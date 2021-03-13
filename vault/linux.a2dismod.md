---
id: linux.a2dismod
title: A2dismod
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# a2dismod

> Disable an Apache module on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2dismod.8.en.html>.

- Disable a module:

`sudo a2dismod {{module}}`

- Don't show informative messages:

`sudo a2dismod --quiet {{module}}`

