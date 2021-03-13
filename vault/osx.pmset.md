---
id: osx.pmset
title: Pmset
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pmset

> Configure macOS power management settings, as one might do in System Preferences > Energy Saver.
> Commands that modify settings must begin with `sudo`.

- Display the current power management settings:

`pmset -g`

- Display the current power source and battery levels:

`pmset -g batt`

- Put display to sleep immediately:

`pmset displaysleepnow`

- Set display to never sleep when on charger power:

`sudo pmset -c displaysleep 0`

- Set display to sleep after 15 minutes when on battery power:

`sudo pmset -b displaysleep 15`

- Schedule computer to automatically wake up every weekday at 9 AM:

`sudo pmset repeat wake MTWRF 09:00:00`

- Restore to system defaults:

`sudo pmset -a displaysleep 10 disksleep 10 sleep 30 womp 1`

