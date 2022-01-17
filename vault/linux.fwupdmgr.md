---
id: linux.fwupdmgr
title: Fwupdmgr
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fwupdmgr

> A tool for updating device firmware, including UEFI, using `fwupd`.
> More information: <https://fwupd.org/>.

- Display all devices detected by fwupd:

`fwupdmgr get-devices`

- Download the latest firmware metadata from LVFS:

`fwupdmgr refresh`

- List the updates available for devices on your system:

`fwupdmgr get-updates`

- Install firmware updates:

`fwupdmgr update`

