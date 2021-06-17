---
id: linux.radeontop
title: Radeontop
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# radeontop

> Show utilisation of AMD GPUs.
> More information: <https://github.com/clbr/radeontop>.

- Show the utilisation of the default AMD GPU:

`sudo radeontop`

- Enable colourised output:

`sudo radeontop --colour`

- Select a specific GPU (the bus number is the first number in the output of `lspci`):

`sudo radeontop --bus {{bus_number}}`

- Specify the display refresh rate (higher means more GPU overhead):

`sudo radeontop --ticks {{samples_per_second}}`

