---
id: common.f3probe
title: F3probe
desc: ''
updated: 1615663978709
created: 1615663978709
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# f3probe

> Probe a block device (e.g. a flash drive or a microSD card) for counterfeit flash memory.
> See also `f3read`, `f3write`, `f3fix`.
> More information: <https://github.com/AltraMayor/f3>.

- Probe a block device:

`sudo f3probe {{path/to/block_device}}`

- Use the minimum about of RAM possible:

`sudo f3probe --min-memory {{path/to/block_device}}`

- Time disk operations:

`sudo f3probe --time-ops {{path/to/block_device}}`

