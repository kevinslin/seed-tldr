---
id: common.solo
title: Solo
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# solo

> Interact with Solo hardware security keys.
> More information: <https://github.com/solokeys/solo-python>.

- List connected Solos:

`solo ls`

- Update the currently connected Solo's firmware to the latest version:

`solo key update`

- Blink the led of a specific Solo:

`solo key wink --serial {{serial_number}}`

- Generate random bytes using the currently connected Solo's secure random number generator:

`solo key rng raw`

- Monitor the serial output of a Solo:

`solo monitor {{path/to/serial_port}}`

