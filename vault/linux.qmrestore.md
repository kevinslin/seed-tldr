---
id: linux.qmrestore
title: Qmrestore
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qmrestore

> Restore QemuServer vzdump Backups.
> More information: <https://pve.proxmox.com/pve-docs/qmrestore.1.html>.

- Restore KVM-based virtual machine to local storage:

`qmrestore {{/var/lib/vz/dump/backup_file.vma.lzo}} {{vm_id}} --storage {{local}}`

