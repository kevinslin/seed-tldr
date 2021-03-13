---
id: common.clear
title: Clear
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# clear

> Clears the screen of the terminal.

- Clear the screen (equivalent to pressing Control-L in Bash shell):

`clear`

- Clear the screen but keep the terminal's scrollback buffer:

`clear -x`

- Indicate the type of terminal to clean (defaults to the value of the environment variable `TERM`):

`clear -T {{type_of_terminal}}`

- Show the version of `ncurses` used by `clear`:

`clear -V`

