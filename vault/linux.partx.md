---
id: linux.partx
title: Partx
desc: ''
updated: 1615663978752
created: 1615663978752
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# partx

> Parse a partition table and tell the kernel about it.
> More information: <https://man7.org/linux/man-pages/man8/partx.8.html>.

- List the partitions on a block device or disk image:

`sudo partx --list {{path/to/device_or_disk_image}}`

- Add all the paritions found in a given block device to the kernel:

`sudo partx --add --verbose {{path/to/device_or_disk_image}}`

- Delete all the partitions found from the kernel (does not alter partitions on disk):

`sudo partx --delete {{path/to/device_or_disk_image}}`
