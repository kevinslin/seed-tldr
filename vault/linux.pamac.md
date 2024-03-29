---
id: linux.pamac
title: Pamac
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pamac

> A command-line utility for the GUI package manager pamac.
> If you can't see the AUR packages, enable it in `/etc/pamac.conf` or in the GUI.
> More information: <https://wiki.manjaro.org/index.php/Pamac>.

- Install a new package:

`pamac install {{package_name}}`

- Remove a package and its no longer required dependencies (orphans):

`pamac remove --orphans {{package_name}}`

- Search the package database for a package:

`pamac search {{package_name}}`

- List installed packages:

`pamac list --installed`

- Check for package updates:

`pamac checkupdates`

- Upgrade all packages:

`pamac upgrade`

