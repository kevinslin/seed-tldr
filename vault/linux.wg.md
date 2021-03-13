---
id: linux.wg
title: Wg
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wg

> Manage the configuration of WireGuard interfaces.
> More information: <https://www.wireguard.com/quickstart/>.

- Check status of currently active interfaces:

`sudo wg`

- Print a new private key:

`wg genkey`

- Print a new public key:

`echo {{private_key}} | wg pubkey`

- Generate a public and private key:

`wg genkey | tee {{privatekey.txt}} | wg pubkey > {{publickey.txt}}`

