---
id: common.virt-install
title: Virt Install
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-install

> Create virtual machines with libvirt and begin OS installation.
> More information: <https://virt-manager.org/>.

- Create a virtual machine with 1 GiB RAM and 12 GiB storage and start Debian installation:

`virt-install --name {{vm_name}} --memory {{1024}} --disk path={{path/to/image.qcow2}},size={{12}} --cdrom {{path/to/debian.iso}}`

