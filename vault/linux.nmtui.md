---
id: linux.nmtui
title: Nmtui
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
# nmtui

> Text user interface for controlling NetworkManager.
> Use arrow keys to navigate, enter to select an option.

- Open the user interface:

`nmtui`

- Show a list of available connections, with the option to activate or deactivate them:

`nmtui connect`

- Connect to a given network:

`nmtui connect {{name|uuid|device|SSID}}`

- Edit/Add/Delete a given network:

`nmtui edit {{name|id}}`

- Set the system hostname:

`nmtui hostname`

