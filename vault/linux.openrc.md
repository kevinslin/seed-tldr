---
id: linux.openrc
title: Openrc
desc: ''
updated: 1615663978751
created: 1615663978751
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openrc

> The OpenRC service manager.
> See also `rc-status`, `rc-update`, and `rc-service`.
> More information: <https://wiki.gentoo.org/wiki/OpenRC>.

- Change to a specific runlevel:

`sudo openrc {{runlevel_name}}`

- Change to a specific runlevel, but don't stop any existing services:

`sudo openrc --no-stop {{runlevel_name}}`

