---
id: windows.scoop
title: Scoop
desc: ''
updated: 1615663978764
created: 1615663978764
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scoop

> A command-line installer for Windows.
> More information: <https://scoop.sh>.

- Install a package:

`scoop install {{package}}`

- Remove a package:

`scoop uninstall {{package}}`

- Update all installed packages:

`scoop update *`

- List installed packages:

`scoop list`

- Display information about a package:

`scoop info {{package}}`

- Search for a package:

`scoop search {{package}}`

- Remove old versions of all packages and clear the download cache:

`scoop cleanup -k *`

