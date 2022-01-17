---
id: linux.a2disconf
title: A2disconf
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
# a2disconf

> Disable an Apache configuration file on Debian-based OSes.
> More information: <https://manpages.debian.org/latest/apache2/a2disconf.8.en.html>.

- Disable a configuration file:

`sudo a2disconf {{configuration_file}}`

- Don't show informative messages:

`sudo a2disconf --quiet {{configuration_file}}`

