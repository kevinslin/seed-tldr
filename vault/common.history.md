---
id: common.history
title: History
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# history

> Command Line history.

- Display the commands history list with line numbers:

`history`

- Display the last 20 commands:

`history {{20}}`

- Clear the commands history list (only for current `bash` shell):

`history -c`

- Overwrite history file with history of current `bash` shell (often combined with `history -c` to purge history):

`history -w`

- Delete the history entry at the specified offset:

`history -d {{offset}}`

