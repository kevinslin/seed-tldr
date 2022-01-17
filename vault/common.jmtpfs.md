---
id: common.jmtpfs
title: Jmtpfs
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jmtpfs

> FUSE-based filesystem for accessing MTP devices.
> More information: <https://manned.org/jmtpfs>.

- Mount an MTP device to a directory:

`jmtpfs {{path/to/directory}}`

- Set mount options:

`jmtpfs -o {{allow_other,auto_unmount}} {{path/to/directory}}`

- List available MTP devices:

`jmtpfs --listDevices`

- If multiple devices are present, mount a specific device:

`jmtpfs -device={{bus_id}},{{device_id}} {{path/to/directory}}`

- Unmount MTP device:

`fusermount -u {{path/to/directory}}`

