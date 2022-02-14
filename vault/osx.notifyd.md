---
id: osx.notifyd
title: Notifyd
desc: ''
updated: 1644840636310
created: 1644840636310
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# notifyd

> Notification server.
> It should not be invoked manually.
> More information: <https://www.manpagez.com/man/8/notifyd/>.

- Start the daemon:

`notifyd`

- Log debug messages to the default log file (`/var/log/notifyd.log`):

`notifyd -d`

- Log debug messages to an alternate log file:

`notifyd -d -log_file {{path/to/log}}`

