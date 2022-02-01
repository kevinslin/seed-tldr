---
id: linux.vcgencmd
title: Vcgencmd
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vcgencmd

> Print system information for a Raspberry Pi.
> More information: <https://www.raspberrypi.org/documentation/raspbian/applications/vcgencmd.md>.

- List all available commands:

`vcgencmd commands`

- Print the current CPU temperature:

`vcgencmd measure_temp`

- Print the current voltage:

`vcgencmd measure_volts`

- Print the throttled state of the system as a bit pattern:

`vcgencmd get_throttled`

- Print the bootloader config (only available on Raspberry Pi 4 models):

`vcgencmd bootloader_config`

- Display Help:

`vcgencmd --help`

