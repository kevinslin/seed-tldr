---
id: common.stty
title: Stty
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

