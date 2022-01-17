---
id: linux.minicom
title: Minicom
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minicom

> A program to communicate with the serial interface of a device.
> More information: <https://manned.org/minicom>.

- Open a given serial port:

`sudo minicom --device {{/dev/ttyUSB0}}`

- Open a given serial port with a given baud rate:

`sudo minicom --device {{/dev/ttyUSB0}} --baudrate {{115200}}`

- Enter the configuration menu before communicating with a given serial port:

`sudo minicom --device {{/dev/ttyUSB0}} --setup`

