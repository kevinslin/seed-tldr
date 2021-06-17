---
id: linux.openvpn3
title: Openvpn3
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openvpn3

> OpenVPN 3 Linux client.
> More information: <https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux>.

- Start a new VPN session:

`openvpn3 session-start --config {{path/to/config.conf}}`

- List established sessions:

`openvpn3 sessions-list`

- Disconnect the currently established session started with given configuration:

`openvpn3 session-manage --config {{path/to/config.conf}} --disconnect`

- Import VPN configuration:

`openvpn3 config-import --config {{path/to/config.conf}}`

- List imported configurations:

`openvpn3 configs-list`

