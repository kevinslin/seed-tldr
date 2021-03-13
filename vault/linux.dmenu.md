---
id: linux.dmenu
title: Dmenu
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dmenu

> Dynamic menu.
> Creates a menu from a text input with each item on a new line.

- Display a menu of the output of the `ls` command:

`{{ls}} | dmenu`

- Display a menu with custom items separated by a new line (`\n`):

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu`

- Let the user choose between multiple items and save the selected one to a file:

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu > {{color.txt}}`

- Launch dmenu on a specific monitor:

`ls | dmenu -m {{1}}`

- Display dmenu at the bottom of the screen:

`ls | dmenu -b`

