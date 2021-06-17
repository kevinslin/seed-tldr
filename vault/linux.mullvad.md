---
id: linux.mullvad
title: Mullvad
desc: ''
updated: 1623965016165
created: 1623965016165
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mullvad

> CLI client for Mullvad VPN.
> More information: <https://mullvad.net/>.

- Link your mullvad account with the specified account number:

`mullvad account set {{account_number}}`

- Enable LAN access while VPN is on:

`mullvad lan set allow`

- Establish the VPN tunnel:

`mullvad connect`

- Check status of VPN tunnel:

`mullvad status`

