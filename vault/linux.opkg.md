---
id: linux.opkg
title: Opkg
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
# opkg

> A lightweight package manager used to install OpenWrt packages.

- Install a package:

`opkg install {{package}}`

- Remove a package:

`opkg remove {{package}}`

- Update the list of available packages:

`opkg update`

- Upgrade all the installed packages:

`opkg upgrade`

- Upgrade one or more specific package(s):

`opkg upgrade {{package(s)}}`

- Display information for a specific package:

`opkg info {{package}}`

- List all the available packages:

`opkg list`

