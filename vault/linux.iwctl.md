---
id: linux.iwctl
title: Iwctl
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iwctl

> A command-line tool for controlling the iwd network supplicant.
> More information: <https://iwd.wiki.kernel.org/gettingstarted>.

- Start the interactive mode, in this mode you can enter the commands directly, with autocompletion:

`iwctl`

- Call general help:

`iwctl --help`

- Display your wifi stations:

`iwctl station list`

- Start looking for networks with a station:

`iwctl station {{station}} scan`

- Display the networks found by a station:

`iwctl station {{station}} get-networks`

- Connect to a network with a station, if credentials are needed they will be asked:

`iwctl station {{station}} connect {{network_name}}`

