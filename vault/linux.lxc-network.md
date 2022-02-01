---
id: linux.lxc-network
title: Lxc Network
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lxc network

> Manage networks for LXD containers.
> More information: <https://linuxcontainers.org/lxd/docs/master/networks>.

- List all available networks:

`lxc network list`

- Show the configuration of a specific network:

`lxc network show {{network_name}}`

- Add a running instance to a specific network:

`lxc network attach {{network_name}} {{container_name}}`

- Create a new managed network:

`lxc network create {{network_name}}`

- Set a bridge interface of a specific network:

`lxc network set {{network_name}} bridge.external_interfaces {{eth0}}`

- Disable NAT for a specific network:

`lxc network set {{network_name}} ipv{{4}}.nat false`

