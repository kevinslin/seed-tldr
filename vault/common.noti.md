---
id: common.noti
title: Noti
desc: ''
updated: 1623965306200
created: 1623965306200
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

