---
id: linux.wg-quick
title: Wg Quick
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wg-quick

> Quickly set up WireGuard tunnels based on config files.
> More information: <https://www.wireguard.com/quickstart/>.

- Set up a VPN tunnel:

`wg-quick up {{interface_name}}`

- Delete a VPN tunnel:

`wg-quick down {{interface_name}}`

