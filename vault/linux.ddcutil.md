---
id: linux.ddcutil
title: Ddcutil
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ddcutil

> Control the settings of connected displays via DDC/CI.
> This command requires the kernel module `i2c-dev` to be loaded. See also: `modprobe`.
> More information: <https://www.ddcutil.com>.

- List all compatible displays:

`ddcutil detect`

- Change the brightness (option 0x10) of display 1 to 50%:

`ddcutil --display {{1}} setvcp {{10}} {{50}}`

- Increase the contrast (option 0x12) of display 1 by 5%:

`ddcutil -d {{1}} setvcp {{12}} {{+}} {{5}}`

- Read the settings of display 1:

`ddcutil -d {{1}} getvcp {{ALL}}`

