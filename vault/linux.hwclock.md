---
id: linux.hwclock
title: Hwclock
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hwclock

> Used for reading or changing the hardware clock. Usually requires root.

- Display the current time as reported by the hardware clock:

`hwclock`

- Write the current software clock time to the hardware clock (sometimes used during system setup):

`hwclock --systohc`

- Write the current hardware clock time to the software clock:

`hwclock --hctosys`

