---
id: linux.shutdown
title: Shutdown
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shutdown

> Shutdown and reboot the system.

- Power off (halt) immediately:

`shutdown -h now`

- Reboot immediately:

`shutdown -r now`

- Reboot in 5 minutes:

`shutdown -r +{{5}} &`

- Shutdown at 1:00 pm (Uses 24h clock):

`shutdown -h 13:00`

- Cancel a pending shutdown/reboot operation:

`shutdown -c`

