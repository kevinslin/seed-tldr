---
id: common.screen
title: Screen
desc: ''
updated: 1615655543084
created: 1615655543084
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# screen

> Hold a session open on a remote server. Manage multiple windows with a single SSH connection.

- Start a new screen session:

`screen`

- Start a new named screen session:

`screen -S {{session_name}}`

- Start a new daemon and log the output to `screenlog.x`:

`screen -dmLS {{session_name}} {{command}}`

- Show open screen sessions:

`screen -ls`

- Reattach to an open screen:

`screen -r {{session_name}}`

- Detach from inside a screen:

`Ctrl + A, D`

- Kill the current screen session:

`Ctrl + A, K`

- Kill a detached screen:

`screen -X -S {{session_name}} quit`

