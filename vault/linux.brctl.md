---
id: linux.brctl
title: Brctl
desc: ''
updated: 1623965306219
created: 1623965306219
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# brctl

> Ethernet bridge administration.

- Show a list with information about currently existing ethernet bridges:

`sudo brctl show`

- Create a new ethernet bridge interface:

`sudo brctl add {{bridge_name}}`

- Delete an existing ethernet bridge interface:

`sudo brctl del {{bridge_name}}`

- Add an interface to an existing bridge:

`sudo brctl addif {{bridge_name}} {{interface_name}}`

- Remove an interface from an existing bridge:

`sudo brctl delif {{bridge_name}} {{interface_name}}`

