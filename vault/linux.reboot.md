---
id: linux.reboot
title: Reboot
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reboot

> Reboot the system.
> More information: <https://www.man7.org/linux/man-pages/man8/reboot.8.html>.

- Reboot the system:

`reboot`

- Power off the system (same as `poweroff`):

`reboot --poweroff`

- Halt the system (same as `halt`):

`reboot --halt`

- Reboot immediately without contacting the system manager:

`reboot --force --force`

- Write the wtmp shutdown entry without rebooting the system:

`reboot --wtmp-only`

