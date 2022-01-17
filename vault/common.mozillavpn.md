---
id: common.mozillavpn
title: Mozillavpn
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mozillavpn

> A Virtual Private Network from the makers of Firefox.
> More information: <https://github.com/mozilla-mobile/mozilla-vpn-client/wiki/Command-line-interface>.

- Log in with an interactive prompt:

`mozillavpn login`

- Connect to Mozilla VPN:

`mozillavpn activate`

- Display the connection status:

`mozillavpn status`

- List available servers:

`mozillavpn servers`

- Select a specific server:

`mozillavpn select {{server_name}}`

- Disconnect from Mozilla VPN:

`mozillavpn deactivate`

- Log out:

`mozillavpn logout`

- Display help for a subcommand:

`mozillavpn {{subcommand}} --help`

