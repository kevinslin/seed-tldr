---
id: osx.shutdown
title: Shutdown
desc: ''
updated: 1644840636312
created: 1644840636312
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shutdown

> Shutdown and reboot the system.
> More information: <https://ss64.com/osx/shutdown.html>.

- Power off (halt) immediately:

`shutdown -h now`

- Sleep immediately:

`shutdown -s now`

- Reboot immediately:

`shutdown -r now`

- Reboot in 5 minutes:

`shutdown -r "+{{5}}"`

- Power off (halt) at 1:00 pm (Uses 24h clock):

`shutdown -h {{1300}}`

- Reboot on May 10th 2042 at 11:30 am (Input format: YYMMDDHHMM):

`shutdown -r {{4205101130}}`

