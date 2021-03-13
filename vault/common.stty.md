---
id: common.stty
title: Stty
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stty

> Set options for a terminal device interface.

- Display all settings for the current terminal:

`stty -a`

- Set the number of rows:

`stty rows {{rows}}`

- Set the number of columns:

`stty cols {{cols}}`

- Get the actual transfer speed of a device:

`stty -f {{path/to/device_file}} speed`

- Reset all modes to reasonable values for the current terminal:

`stty sane`

