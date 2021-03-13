---
id: common.noti
title: Noti
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# noti

> Monitor a process and trigger a banner notification.
> More information: <https://github.com/variadico/noti>.

- Display a notification when tar finishes compressing files:

`noti {{tar -cjf example.tar.bz2 example/}}`

- Display a notification even when you put it after the command to watch:

`{{command_to_watch}}; noti`

- Monitor a process by PID and trigger a notification when the PID disappears:

`noti -w {{process_id}}`

