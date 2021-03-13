---
id: linux.bluetoothctl
title: Bluetoothctl
desc: ''
updated: 1615663978742
created: 1615663978742
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bluetoothctl

> Handling bluetooth devices from the shell.

- Enter the bluetoothctl shell:

`bluetoothctl`

- List devices:

`bluetoothctl -- devices`

- Pair a device:

`bluetoothctl -- pair {{mac_address}}`

- Remove a device:

`bluetoothctl -- remove {{mac_address}}`

- Connect a paired device:

`bluetoothctl -- connect {{mac_address}}`

- Disconnect a paired device:

`bluetoothctl -- disconnect {{mac_address}}`

