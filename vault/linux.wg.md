---
id: linux.wg
title: Wg
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

