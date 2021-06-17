---
id: linux.virt-manager
title: Virt Manager
desc: ''
updated: 1623965306231
created: 1623965306231
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-manager

> CLI launcher for virt-manager, a desktop user interface for managing KVM and Xen virtual machines and LXC containers.
> More information: <https://manpages.ubuntu.com/manpages/man1/virt-manager.1.html>.

- Launch virt-manager:

`virt-manager`

- Connect to a hypervisor:

`virt-manager --connect {{hypervisor_uri}}`

- Don't fork virt-manager process into background on startup:

`virt-manager --no-fork`

- Print debug output:

`virt-manager --debug`

- Open the "New VM" wizard:

`virt-manager --show-domain-creator`

- Show domain details window:

`virt-manager --show-domain-editor {{name|id|uuid}}`

- Show domain performance window:

`virt-manager --show-domain-performance {{name|id|uuid}}`

- Show connection details window:

`virt-manager --show-host-summary`

