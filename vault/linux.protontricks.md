---
id: linux.protontricks
title: Protontricks
desc: ''
updated: 1615655543108
created: 1615655543108
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# protontricks

> A simple wrapper that does winetricks things for Proton enabled games, requires Winetricks.
> More information: <https://github.com/Matoking/protontricks>.

- Show the protontricks help message:

`protontricks`

- Run the protontricks GUI:

`protontricks --gui`

- Run winetricks for a specific game:

`protontricks {{appid}} {{winetricks_args}}`

- Run a command within a games installation directory:

`protontricks -c {{command}} {{appid}}`

