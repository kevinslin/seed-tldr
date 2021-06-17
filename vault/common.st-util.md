---
id: common.st-util
title: St Util
desc: ''
updated: 1623965306211
created: 1623965306211
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# st-util

> Run GDB (GNU Debugger) server to interact with STM32 ARM Cortex microcontoller.
> More information: <https://github.com/texane/stlink>.

- Run GDB server on port 4500:

`st-util -p {{4500}}`

- Connect to GDB server:

`(gdb) target extended-remote {{localhost}}:{{4500}}`

- Write firmware to device:

`(gdb) load {{firmware.elf}}`

