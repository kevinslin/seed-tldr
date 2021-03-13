---
id: common.st-flash
title: St Flash
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# st-flash

> Flash binary files to STM32 ARM Cortex microcontrollers.
> More information: <https://github.com/texane/stlink>.

- Read 4096 bytes from the device starting from 0x8000000:

`st-flash read {{firmware}}.bin {{0x8000000}} {{4096}}`

- Write firmware to device starting from 0x8000000:

`st-flash write {{firmware}}.bin {{0x8000000}}`

- Erase firmware from device:

`st-flash erase`

