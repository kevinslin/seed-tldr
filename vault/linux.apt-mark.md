---
id: linux.apt-mark
title: Apt Mark
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-mark

> Utility to change the status of installed packages.

- Mark a package as automatically installed:

`sudo apt-mark auto {{package_name}}`

- Hold a package at its current version and prevent updates to it:

`sudo apt-mark hold {{package_name}}`

- Allow a package to be updated again:

`sudo apt-mark unhold {{package_name}}`

- Show manually installed packages:

`apt-mark showmanual`

- Show held packages that aren't being updated:

`apt-mark showhold`

