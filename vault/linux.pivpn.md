---
id: linux.pivpn
title: Pivpn
desc: ''
updated: 1623965306227
created: 1623965306227
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pivpn

> Easy security-hardened OpenVPN setup and manager.
> Originally designed for the Raspberry Pi, but works on other Linux devices too.
> More information: <http://www.pivpn.io/>.

- Add a new client device:

`sudo pivpn add`

- List all client devices:

`sudo pivpn list`

- List currently connected devices and their statistics:

`sudo pivpn clients`

- Revoke a previously authenticated device:

`sudo pivpn revoke`

- Uninstall PiVPN:

`sudo pivpn uninstall`

