---
id: linux.blkdiscard
title: Blkdiscard
desc: ''
updated: 1642441815088
created: 1642441815088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# blkdiscard

> Discards device sectors on storage devices. Useful for SSDs.
> More information: <https://manned.org/blkdiscard>.

- Discard all sectors on a device, removing all data:

`blkdiscard /dev/{{device}}`

- Securely discard all blocks on a device, removing all data:

`blkdiscard --secure /dev/{{device}}`

- Discard the first 100 MB of a device:

`blkdiscard --length {{100MB}} /dev/{{device}}`

