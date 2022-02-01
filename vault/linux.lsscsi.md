---
id: linux.lsscsi
title: Lsscsi
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsscsi

> List SCSI devices (or hosts) and their attributes.
> More information: <https://manned.org/lspci>.

- List all SCSI devices:

`lsscsi`

- List all SCSI devices with detailed attributes:

`lsscsi -L`

- List all SCSI devices with human-readable disk capacity:

`lsscsi -s`

