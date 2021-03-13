---
id: linux.snap
title: Snap
desc: ''
updated: 1615663978755
created: 1615663978755
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# snap

> Tool for managing the "snap" self-contained software packages.
> Similar to what `apt` is for ".deb".

- Search for a package:

`snap find {{package_name}}`

- Install a package:

`snap install {{package_name}}`

- Update a package:

`snap refresh {{package_name}}`

- Update all packages:

`snap refresh`

- Display basic information about installed snap software:

`snap list`

- Uninstall a package:

`snap remove {{package_name}}`

- Check for recent snap changes in the system:

`snap changes`

