---
id: linux.timedatectl
title: Timedatectl
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
# timedatectl

> Control the system time and date.
> More information: <https://manned.org/timedatectl.1>.

- Check the current system clock time:

`timedatectl`

- Set the local time of the system clock directly:

`timedatectl set-time "{{yyyy-MM-dd hh:mm:ss}}"`

- List available timezones:

`timedatectl list-timezones`

- Set the system timezone:

`timedatectl set-timezone {{timezone}}`

- Enable Network Time Protocol (NTP) synchronization:

`timedatectl set-ntp on`

