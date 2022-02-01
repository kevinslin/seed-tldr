---
id: linux.a2query
title: A2query
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
# a2query

> Retrieve runtime configuration from Apache on Debian-based OSes.
> More information: <https://manpages.debian.org/latest/apache2/a2query.html>.

- List enabled Apache modules:

`sudo a2query -m`

- Check if a specific module is installed:

`sudo a2query -m {{module_name}}`

- List enabled virtual hosts:

`sudo a2query -s`

- Display the currently enabled Multi Processing Module:

`sudo a2query -M`

- Display the Apache version:

`sudo a2query -v`

