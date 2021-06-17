---
id: linux.a2enconf
title: A2enconf
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
# a2enconf

> Enable an Apache configuration file on Debian-based OSes.
> More information: <https://manpages.debian.org/latest/apache2/a2enconf.8.en.html>.

- Enable a configuration file:

`sudo a2enconf {{configuration_file}}`

- Don't show informative messages:

`sudo a2enconf --quiet {{configuration_file}}`

