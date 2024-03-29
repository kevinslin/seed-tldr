---
id: linux.rig
title: Rig
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rig

> Utility to piece together a random first name, last name, street number and address, along with a geographically consistent (ie, they all match the same area) city, state, ZIP code, and area code.
> More information: <https://manned.org/rig>.

- Display a random name (male or female) and address:

`rig`

- Display a [m]ale (or [f]emale) random name and address:

`rig -{{m|f}}`

- Use data files from a specific directory (default is `/usr/share/rig`):

`rig -d {{path/to/directory}}`

- Display a specific number of identities:

`rig -c {{number}}`

- Display a specific number of female identities:

`rig -f -c {{number}}`

