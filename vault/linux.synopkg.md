---
id: linux.synopkg
title: Synopkg
desc: ''
updated: 1642441815114
created: 1642441815114
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# synopkg

> Package management utility for Synology DiskStation Manager.
> More information: <https://www.synology.com/dsm>.

- List the names of installed packages:

`synopkg list --name`

- List packages which depend on a specific package:

`synopkg list --depend-on {{package}}`

- Start/Stop a package:

`sudo synopkg {{start|stop}} {{package}}`

- Print the status of a package:

`synopkg status {{package}}`

- Uninstall a package:

`sudo synopkg uninstall {{package}}`

- Check if updates are available for a package:

`synopkg checkupdate {{package}}`

- Upgrade all packages to the latest version:

`sudo synopkg upgradeall`

- Install a package from a synopkg file:

`sudo synopkg install {{path/to/package.spk}}`

