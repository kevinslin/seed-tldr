---
id: linux.winetricks
title: Winetricks
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# winetricks

> Manage Wine virtual Windows environments.
> More information: <https://wiki.winehq.org/Winetricks>.

- Start a graphical setup at the default Wine location:

`winetricks`

- Specify a custom Wine directory to run winetricks in:

`WINEPREFIX={{path/to/wine_directory}} winetricks`

- Install a Windows DLL or component to the default Wine directory:

`winetricks {{package}}`

