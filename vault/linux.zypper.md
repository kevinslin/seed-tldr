---
id: linux.zypper
title: Zypper
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zypper

> SUSE & openSUSE package management utility.

- Synchronize list of packages and versions available:

`zypper refresh`

- Install a new package:

`zypper install {{package}}`

- Remove a package:

`zypper remove {{package}}`

- Upgrade installed packages to newest available versions:

`zypper update`

- Search package via keyword:

`zypper search {{keyword}}`

