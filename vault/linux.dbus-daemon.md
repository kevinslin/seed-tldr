---
id: linux.dbus-daemon
title: Dbus Daemon
desc: ''
updated: 1623965016160
created: 1623965016160
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dbus-daemon

> The D-Bus message daemon, allowing multiple programs to exchange messages.

- Run the daemon with a configuration file:

`dbus-daemon --config-file {{path/to/file}}`

- Run the daemon with the standard per-login-session message bus configuration:

`dbus-daemon --session`

- Run the daemon with the standard systemwide message bus configuration:

`dbus-daemon --system`

- Set the address to listen on and override the configuration value for it:

`dbus-daemon --address {{address}}`

- Output the process id to stdout:

`dbus-daemon --print-pid`

- Force the message bus to write to the system log for messages:

`dbus-daemon --syslog`

