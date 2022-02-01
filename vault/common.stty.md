---
id: common.stty
title: Stty
desc: ''
updated: 1642441815073
created: 1642441815073
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stty

> Set options for a terminal device interface.
> More information: <https://www.gnu.org/software/coreutils/stty>.

- Display all settings for the current terminal:

`stty -a`

- Set the number of rows:

`stty rows {{rows}}`

- Set the number of columns:

`stty cols {{cols}}`

- Get the actual transfer speed of a device:

`stty -F {{path/to/device_file}} speed`

- Reset all modes to reasonable values for the current terminal:

`stty sane`

