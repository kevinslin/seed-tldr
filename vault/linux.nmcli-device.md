---
id: linux.nmcli-device
title: Nmcli Device
desc: ''
updated: 1646802118864
created: 1646802118864
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli device

> Hardware device management with NetworkManager.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Print the statuses of all network interfaces:

`nmcli device status`

- Print the available Wi-Fi access points:

`nmcli device wifi`

- Connect to the Wi-Fi network with a specified name and password:

`nmcli device wifi connect {{ssid}} password {{password}}`

- Print password and QR code for the current Wi-Fi network:

`nmcli device wifi show-password`

