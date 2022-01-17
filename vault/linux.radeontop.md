---
id: linux.radeontop
title: Radeontop
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# radeontop

> Show utilisation of AMD GPUs.
> May require root privileges depending on your system.
> More information: <https://github.com/clbr/radeontop>.

- Show the utilisation of the default AMD GPU:

`radeontop`

- Enable colored output:

`radeontop --color`

- Select a specific GPU (the bus number is the first number in the output of `lspci`):

`radeontop --bus {{bus_number}}`

- Specify the display refresh rate (higher means more GPU overhead):

`radeontop --ticks {{samples_per_second}}`

