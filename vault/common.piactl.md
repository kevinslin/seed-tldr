---
id: common.piactl
title: Piactl
desc: ''
updated: 1623965306204
created: 1623965306204
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# piactl

> The command-line tool for Private Internet Access, a commercial VPN provider.
> More information: <https://privateinternetaccess.com/helpdesk/kb/articles/pia-desktop-command-line-interface>.

- Log in to Private Internet Access:

`piactl login {{path/to/login_file}}`

- Connect to Private Internet Access:

`piactl connect`

- Disconnect from Private Internet Access:

`piactl disconnect`

- Enable or disable the Private Internet Access daemon in the background:

`piactl background {{enable|disable}}`

- List all available VPN regions:

`piactl get regions`

- Display the current VPN region:

`piactl get region`

- Set your VPN region:

`piactl set region {{region}}`

- Log out of Private Internet Access:

`piactl logout`

