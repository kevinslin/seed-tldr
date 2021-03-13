---
id: linux.vncserver
title: Vncserver
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# vncserver

> Launches a VNC (Virtual Network Computing) desktop.

- Launch a VNC Server on next available display:

`vncserver`

- Launch a VNC Server with specific screen geometry:

`vncserver --geometry {{width}}x{{height}}`

- Kill an instance of VNC Server running on a specific display:

`vncserver --kill :{{display_number}}`

