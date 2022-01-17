---
id: linux.microcom
title: Microcom
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
# microcom

> A minimalistic terminal program, used to access remote devices via a serial, CAN or telnet connection from the console.
> More information: <https://manned.org/microcom>.

- Open a serial port using the specified baud rate:

`microcom --port {{path/to/serial_port}} --speed {{baud_rate}}`

- Establish a telnet connection to the specified host:

`microcom --telnet {{hostname}}:{{port}}`

