---
id: linux.halt
title: Halt
desc: ''
updated: 1642441815097
created: 1642441815097
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# halt

> Halt the system.
> More information: <https://www.man7.org/linux/man-pages/man8/halt.8.html>.

- Halt the system:

`halt`

- Power off the system (same as `poweroff`):

`halt --poweroff`

- Reboot the system (same as `reboot`):

`halt --reboot`

- Halt immediately without contacting the system manager:

`halt --force --force`

- Write the wtmp shutdown entry without halting the system:

`halt --wtmp-only`

