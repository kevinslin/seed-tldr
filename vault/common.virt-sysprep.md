---
id: common.virt-sysprep
title: Virt Sysprep
desc: ''
updated: 1642441815080
created: 1642441815080
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-sysprep

> Reset, unconfigure, or customize a virtual machine image.
> More information: <https://manned.org/virt-sysprep>.

- List all supported operations (enabled operations are indicated with asterisks):

`virt-sysprep --list-operations`

- Run all enabled operations but don't actually apply the changes:

`virt-sysprep --domain {{vm_name}} --dry-run`

- Run only the specified operations:

`virt-sysprep --domain {{vm_name}} --operations {{operation1,operation2,...}}`

- Generate a new `/etc/machine-id` file and enable customizations to be able to change the host name to avoid network conflicts:

`virt-sysprep --domain {{vm_name}} --enable {{customizations}} --hostname {{host_name}} --operation {{machine-id}}`

