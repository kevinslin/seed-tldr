---
id: linux.lsblk
title: Lsblk
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
# lsblk

> Lists information about devices.
> More information: <https://manned.org/lsblk>.

- List all storage devices in a tree-like format:

`lsblk`

- Also list empty devices:

`lsblk -a`

- Print the SIZE column in bytes rather than in a human-readable format:

`lsblk -b`

- Output info about filesystems:

`lsblk -f`

- Use ASCII characters for tree formatting:

`lsblk -i`

- Output info about block-device topology:

`lsblk -t`

- Exclude the devices specified by the comma-separated list of major device numbers:

`lsblk -e {{1,7}}`

- Display a customized summary using a comma-separated list of columns:

`lsblk --output {{NAME}},{{SERIAL}},{{MODEL}},{{TRAN}},{{TYPE}},{{SIZE}},{{FSTYPE}},{{MOUNTPOINT}}`

