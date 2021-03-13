---
id: common.history
title: History
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

