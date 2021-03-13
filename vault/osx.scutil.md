---
id: osx.scutil
title: Scutil
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# scutil

> Manage system configuration parameters.
> Necessitates to be root when setting configuration.

- Display DNS Configuration:

`scutil --dns`

- Display proxy configuration:

`scutil --proxy`

- Get computer name:

`scutil --get ComputerName`

- Set computer name:

`sudo scutil --set ComputerName {{computer_name}}`

- Get hostname:

`scutil --get HostName`

- Set hostname:

`scutil --set HostName {{hostname}}`

