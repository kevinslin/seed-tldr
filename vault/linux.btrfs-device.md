---
id: linux.btrfs-device
title: Btrfs Device
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# btrfs device

> Manage devices in a btrfs filesystem.
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-device>.

- Add one or more devices to a btrfs filesystem:

`sudo btrfs device add {{path/to/block_device1}} [{{path/to/block_device2}}] {{path/to/btrfs_filesystem}}`

- Remove a device from a btrfs filesystem:

`sudo btrfs device remove {{path/to/device|device_id}} [{{...}}]`

- Display error statistics:

`sudo btrfs device stats {{path/to/btrfs_filesystem}}`

- Scan all disks and inform the kernel of all detected btrfs filesystems:

`sudo btrfs device scan --all-devices`

- Display detailed per-disk allocation statistics:

`sudo btrfs device usage {{path/to/btrfs_filesystem}}`

