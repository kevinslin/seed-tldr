---
id: common.qemu-img
title: Qemu Img
desc: ''
updated: 1623965016146
created: 1623965016146
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qemu-img

> Tool for Quick Emulator Virtual HDD image creation and manipulation.

- Create disk image with a specific size (in gigabytes):

`qemu-img create {{image_name.img}} {{gigabytes}}G`

- Show information about a disk image:

`qemu-img info {{image_name.img}}`

- Increase or decrease image size:

`qemu-img resize {{image_name.img}} {{gigabytes}}G`

- Dump the allocation state of every sector of the specified disk image:

`qemu-img map {{image_name.img}}`

- Convert a VMware .vmdk disk image to a KVM .qcow2 disk image:

`qemu-img convert -O qcow2 {{path/to/file/foo.vmdk}} {{path/to/file/foo.qcow2}}`

