---
id: linux.rfkill
title: Rfkill
desc: ''
updated: 1623965016167
created: 1623965016167
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rfkill

> Enable and disable wireless devices.

- List devices:

`rfkill`

- Filter by columns:

`rfkill -o {{ID,TYPE,DEVICE}}`

- Block devices by type (e.g. bluetooth, wlan):

`rfkill block {{bluetooth}}`

- Unblock devices by type (e.g. bluetooth, wlan):

`rfkill unblock {{wlan}}`

- Output in JSON format:

`rfkill -J`

