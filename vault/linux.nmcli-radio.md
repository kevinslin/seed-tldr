---
id: linux.nmcli-radio
title: Nmcli Radio
desc: ''
updated: 1646866913775
created: 1646866913775
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli radio

> Show radio switches status or enable and disable switches.
> See also: `nmcli agent`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show status of Wi-Fi in NetworkManager:

`nmcli radio wifi`

- Turn Wi-Fi on or off in NetworkManager:

`nmcli radio wifi {{on|off}}`

- Show status of WWAN in NetworkManager:

`nmcli radio wwan`

- Turn WWAN on or off in NetworkManager:

`nmcli radio wwan {{on|off}}`

- Show status of both switches in NetworkManager:

`nmcli radio all`

- Turn both switches on or off in NetworkManager:

`nmcli radio all {{on|off}}`

