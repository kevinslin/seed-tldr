---
id: common.virsh-pool-define-as
title: Virsh Pool Define As
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
# virsh pool-define-as

> Create a configuration file in `/etc/libvirt/storage` for a persistent virtual machine storage pool from the provided arguments.
> See also: `virsh`, `virsh-pool-build`, `virsh-pool-start`.
> More information: <https://manned.org/virsh>.

- Create the configuration file for a storage pool called pool_name using `/var/vms` as the underlying storage system:

`virsh pool-define-as --name {{pool_name}} --type {{dir}} --target {{/var/vms}}`

