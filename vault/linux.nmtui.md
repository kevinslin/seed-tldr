---
id: linux.nmtui
title: Nmtui
desc: ''
updated: 1615655543106
created: 1615655543106
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nmtui

> Text user interface for controlling NetworkManager.
> Use arrow keys to navigate, enter to select an option.

- Open the user interface:

`nmtui`

- Show a list of available connections, with the option to activate or deactivate them:

`nmtui connect`

- Connect to a given network:

`nmtui connect {{name|uuid|device|SSID}}`

- Edit/Add/Delete a given network:

`nmtui edit {{name|id}}`

- Set the system hostname:

`nmtui hostname`

