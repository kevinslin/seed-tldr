---
id: linux.scrot
title: Scrot
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# scrot

> Screen capture utility.

- Capture a screenshot and save it to the current directory with the current date as the filename:

`scrot`

- Capture a screenshot and save it as `capture.png`:

`scrot {{capture.png}}`

- Capture a screenshot interactively:

`scrot --select`

- Capture a screenshot from the currently focused window:

`scrot --focused`

- Display a countdown of 10 seconds before taking a screenshot:

`scrot --count --delay {{10}}`

