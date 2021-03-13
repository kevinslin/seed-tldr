---
id: common.st-flash
title: St Flash
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

