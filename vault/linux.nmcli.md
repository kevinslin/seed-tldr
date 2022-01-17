---
id: linux.nmcli
title: Nmcli
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli

> A command-line tool for controlling NetworkManager.
> Some subcommands such as `nmcli monitor` have their own usage documentation.
> More information: <https://manned.org/nmcli>.

- Run an `nmcli` subcommand:

`nmcli {{agent|connection|device|general|help|monitor|networking|radio}} {{command_options}}`

- Display the current version of NetworkManager:

`nmcli --version`

- Display help:

`nmcli --help`

- Display help for a subcommand:

`nmcli {{subcommand}} --help`

