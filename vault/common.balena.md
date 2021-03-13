---
id: common.balena
title: Balena
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# balena

> Interact with the balenaCloud, openBalena and the balena API from the command line.
> More information: <https://www.balena.io/docs/reference/cli/>.

- Login to the balenaCloud account:

`balena login`

- Create a balenaCloud or openBalena application:

`balena app create {{app_name}}`

- List all balenaCloud or openBalena applications within the account:

`balena apps`

- List all devices associated with the balenaCloud or openBalena account:

`balena devices`

- Flash a balenaOS image to a local drive:

`balena local flash {{path/to/balenaos.img}} --drive {{drive_location}}`

