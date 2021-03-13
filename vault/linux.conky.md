---
id: linux.conky
title: Conky
desc: ''
updated: 1615655543097
created: 1615655543097
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# conky

> Light-weight system monitor for X.
> More information: <https://github.com/brndnmtthws/conky>.

- Launch with default, built-in config:

`conky`

- Create a new default config:

`conky -C > ~/.conkyrc`

- Launch conky with a given config file:

`conky -c {{path/to/config}}`

- Start in the background (daemonize):

`conky -d`

- Align conky on the desktop:

`conky -a {{{top,bottom,middle}_{left,right,middle}}}`

- Pause for 5 seconds at startup before launching:

`conky -p {{5}}`

