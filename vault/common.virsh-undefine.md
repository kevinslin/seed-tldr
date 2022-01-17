---
id: common.virsh-undefine
title: Virsh Undefine
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
# virsh-undefine

> Delete a virtual machine.
> More information: <https://manned.org/virsh>.

- Delete only the virtual machine configuration file:

`virsh undefine --domain {{vm_name}}`

- Delete the configuration file and all associated storage volumes:

`virsh undefine --domain {{vm_name}} --remove-all-storage`

- Delete the configuration file and the specified storage volumes using the target name or the source name (as obtained from the `virsh domblklist` command):

`virsh undefine --domain {{vm_name}} --storage {{sda,path/to/source}}`

