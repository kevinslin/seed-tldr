---
id: linux.macchanger
title: Macchanger
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# macchanger

> Command-line utility for manipulating network interface MAC addresses.
> More information: <https://manned.org/macchanger>.

- View the current and permanent MAC addresses of a interface:

`macchanger --show {{interface}}`

- Set interface to a random MAC:

`macchanger --random {{interface}}`

- Set interface to a specific MAC:

`macchanger --mac {{XX:XX:XX:XX:XX:XX}} {{interface}}`

- Reset interface to its permanent hardware MAC:

`macchanger --permanent {{interface}}`

