---
id: linux.systemctl
title: Systemctl
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemctl

> Control the systemd system and service manager.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- List failed units:

`systemctl --failed`

- Start/Stop/Restart/Reload a service:

`systemctl {{start|stop|restart|reload}} {{unit}}`

- Show the status of a unit:

`systemctl status {{unit}}`

- Enable/Disable a unit to be started on bootup:

`systemctl {{enable|disable}} {{unit}}`

- Mask/Unmask a unit to prevent enablement and manual activation:

`systemctl {{mask|unmask}} {{unit}}`

- Reload systemd, scanning for new or changed units:

`systemctl daemon-reload`

- Check if a unit is active:

`systemctl is-active {{unit}}`

- Check if a unit is enabled:

`systemctl is-enabled {{unit}}`

