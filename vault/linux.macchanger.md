---
id: linux.macchanger
title: Macchanger
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# macchanger

> Command-line utility for manipulating network interface MAC addresses.

- View the current and permanent MAC addresses of a interface:

`macchanger --show {{interface}}`

- Set interface to a random MAC:

`macchanger --random {{interface}}`

- Set interface to a specific MAC:

`macchanger --mac {{XX:XX:XX:XX:XX:XX}} {{interface}}`

- Reset interface to its permanent hardware MAC:

`macchanger --permanent {{interface}}`

