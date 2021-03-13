---
id: common.st-info
title: St Info
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# st-info

> Provides information about connected STLink and STM32 devices.
> More information: <https://github.com/texane/stlink>.

- Display amount of program memory available:

`st-info --flash`

- Display amount of sram memory available:

`st-info --sram`

- Display summarized information of the device:

`st-info --probe`

