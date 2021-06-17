---
id: linux.zramctl
title: Zramctl
desc: ''
updated: 1623965016171
created: 1623965016171
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zramctl

> Setup and control zram devices.
> Use `mkfs` or `mkswap` to format zram devices to partitions.

- Check if zram is enabled:

`lsmod | grep -i zram`

- Enable zram with a dynamic number of devices (use `zramctl` to configure devices further):

`sudo modprobe zram`

- Enable zram with exactly 2 devices:

`sudo modprobe zram num_devices={{2}}`

- Find and initialise the next free zram device to a 2GB virtual drive using LZ4 compression:

`sudo zramctl --find --size {{2GB}} --algorithm {{lz4}}`

- List currently initialised devices:

`zramctl`

