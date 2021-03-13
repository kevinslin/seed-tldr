---
id: osx.opensnoop
title: Opensnoop
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# opensnoop

> Tool that tracks file opens on your system.

- Print all file opens as they occur:

`sudo opensnoop`

- Track all file opens by a process by name:

`sudo opensnoop -n {{process_name}}`

- Track all file opens by a process by PID:

`sudo opensnoop -p {{PID}}`

- Track which processes open a specified file:

`sudo opensnoop -f {{path/to/file}}`

