---
id: linux.needrestart
title: Needrestart
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# needrestart

> Check which daemons need to be restarted after library upgrades.
> More information: <https://github.com/liske/needrestart>.

- List outdated processes:

`needrestart`

- Interactively restart services:

`sudo needrestart`

- List outdated processes in [v]erbose or [q]uiet mode:

`needrestart -{{v|q}}`

- Check if the [k]ernel is outdated:

`needrestart -k`

- Check if the CPU microcode is outdated:

`needrestart -w`

- List outdated processes in [b]atch mode:

`needrestart -b`

- List outdated processed using a specific [c]onfiguration file:

`needrestart -c {{path/to/config}}`

- Display help:

`needrestart --help`

