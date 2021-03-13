---
id: common.glances
title: Glances
desc: ''
updated: 1615655543060
created: 1615655543060
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# glances

> A cross-platform system monitoring tool.
> More information: <https://nicolargo.github.io/glances/>.

- Run in terminal:

`glances`

- Run in web server mode to show results in browser:

`glances -w`

- Run in server mode to allow connections from other Glances clients:

`glances -s`

- Connect to a Glances server:

`glances -c {{hostname}}`

- Require a password in (web) server mode:

`glances -s --password`

