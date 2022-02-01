---
id: linux.dphys-swapfile
title: Dphys Swapfile
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dphys-swapfile

> Manage the swap file on Debian-based Linux systems.
> More information: <https://manpages.debian.org/latest/dphys-swapfile/dphys-swapfile.html>.

- Disable the swap file:

`dphys-swapfile swapoff`

- Enable the swap file:

`dphys-swapfile swapon`

- Create a new swap file:

`dphys-swapfile setup`

