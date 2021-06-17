---
id: common.pio-settings
title: Pio Settings
desc: ''
updated: 1623965016144
created: 1623965016144
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio settings

> View and modify PlatformIO settings.
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_settings.html>.

- Display the names, values and descriptions of all PlatformIO settings:

`pio settings get`

- Display the name, value and description of a specific PlatformIO setting:

`pio settings get {{setting}}`

- Set a specific setting value:

`pio settings set {{setting}} {{value}}`

- Reset the values of all modified settings to their factory defaults:

`pio settings reset`

