---
id: windows.tzutil
title: Tzutil
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# tzutil

> A tool for displaying or configuring the system time zone.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tzutil>.

- Get the current time zone:

`tzutil /g`

- Display a list of available time zones:

`tzutil /l`

- Set the system time zone to the specific value:

`tzutil /s {{timezone_id}}`

