---
id: common.avrdude
title: Avrdude
desc: ''
updated: 1642441814996
created: 1642441814996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# avrdude

> Driver program for Atmel AVR microcontrollers programming.
> More information: <https://www.nongnu.org/avrdude/>.

- Read AVR microcontroller:

`avrdude -p {{AVR_device}} -c {{programmer}} -U flash:r:{{file.hex}}:i`

- Write AVR microcontroller:

`avrdude -p {{AVR_device}} -c {{programmer}} -U flash:w:{{file.hex}}`

- List available AVR devices:

`avrdude -p \?`

- List available AVR programmers:

`avrdude -c \?`

