---
id: linux.mknod
title: Mknod
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mknod

> Create block or character device special files.
> More information: <https://www.gnu.org/software/coreutils/mknod>.

- Create a block device:

`sudo mknod {{path/to/device_file}} b {{major_device_number}} {{minor_device_number}}`

- Create a character device:

`sudo mknod {{path/to/device_file}} c {{major_device_number}} {{minor_device_number}}`

- Create a FIFO (queue) device:

`sudo mknod {{path/to/device_file}} p`

- Create a device file with default SELinux security context:

`sudo mknod -Z {{path/to/device_file}} {{type}} {{major_device_number}} {{minor_device_number}}`

