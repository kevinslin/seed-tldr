---
id: common.st-info
title: St Info
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
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

- Display amount of SRAM memory available:

`st-info --sram`

- Display summarized information of the device:

`st-info --probe`

