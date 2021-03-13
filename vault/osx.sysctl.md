---
id: osx.sysctl
title: Sysctl
desc: ''
updated: 1615663978761
created: 1615663978761
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sysctl

> Access kernel state information.

- Show all available variables and their values:

`sysctl -a`

- Show Apple model identifier:

`sysctl -n hw.model`

- Show CPU model:

`sysctl -n machdep.cpu.brand_string`

- Show available CPU features (MMX, SSE, SSE2, SSE3, AES, etc):

`sysctl -n machdep.cpu.features`

- Set a changeable kernel state variable:

`sysctl -w {{section.tunable}}={{value}}`
