---
id: linux.microcom
title: Microcom
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# microcom

> A minimalistic terminal program, used to access remote devices via a serial, CAN or telnet connection from the console.

- Open a serial port using the specified baud rate:

`microcom --port {{path/to/serial_port}} --speed {{baud_rate}}`

- Establish a telnet connection to the specified host:

`microcom --telnet {{hostname}}:{{port}}`

