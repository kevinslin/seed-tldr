---
id: linux.flashrom
title: Flashrom
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flashrom

> Read, write, verify and erase flash chips.
> More information: <https://manned.org/flashrom>.

- Probe the chip, ensuring the wiring is correct:

`flashrom --programmer {{programmer}}`

- Read flash and save it to a file:

`flashrom -p {{programmer}} --read {{path/to/file}}`

- Write a file to the flash:

`flashrom -p {{programmer}} --write {{path/to/file}}`

- Verify the flash against a file:

`flashrom -p {{programmer}} --verify {{path/to/file}}`

- Probe the chip using Raspberry Pi:

`flashrom -p {{linux_spi:dev=/dev/spidev0.0}}`

