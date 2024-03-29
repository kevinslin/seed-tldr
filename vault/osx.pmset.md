---
id: osx.pmset
title: Pmset
desc: ''
updated: 1642441815122
created: 1642441815122
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pmset

> Configure macOS power management settings, as one might do in System Preferences > Energy Saver.
> Commands that modify settings must begin with `sudo`.
> More information: <https://ss64.com/osx/pmset.html>.

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

