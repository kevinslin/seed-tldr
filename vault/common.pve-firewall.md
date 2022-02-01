---
id: common.pve-firewall
title: Pve Firewall
desc: ''
updated: 1642441815063
created: 1642441815063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pve-firewall

> Manage Proxmox VE Firewall.
> More information: <https://pve.proxmox.com/wiki/Firewall>.

- Compile and print all firewall rules:

`pve-firewall compile`

- Show information about the local network:

`pve-firewall localnet`

- Restart the Proxmox VE Firewall service:

`pve-firewall restart`

- Start the Proxmox VE Firewall service:

`pve-firewall start`

- Stop the Proxmox VE Firewall service:

`pve-firewall stop`

- Simulate all firewall rules:

`pve-firewall simulate`

- Show the status of Proxmox VE Firewall:

`pve-firewall status`

