---
id: linux.fallocate
title: Fallocate
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fallocate

> Reserve or deallocate disk space to files.
> The utility allocates space without zeroing.

- Reserve a file taking up 700MB of disk space:

`fallocate --length {{700M}} {{path/to/file}}`

- Shrink an already allocated file by 200MB:

`fallocate --collapse-range --length {{200M}} {{path/to/file}}`

- Shrink 20MB of space after 100MB in a file:

`fallocate --collapse-range --offset {{100M}} --length {{20M}} {{path/to/file}}`

