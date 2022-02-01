---
id: linux.partprobe
title: Partprobe
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# partprobe

> Notify the operating system kernel of partition table changes.
> More information: <https://manned.org/partprobe>.

- Notify the operating system kernel of partition table changes:

`sudo partprobe`

- Notify the kernel of partition table changes and show a summary of devices and their partitions:

`sudo partprobe --summary`

- Show a summary of devices and their partitions but don't notify the kernel:

`sudo partprobe --summary --dry-run`

