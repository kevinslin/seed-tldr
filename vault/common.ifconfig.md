---
id: common.ifconfig
title: Ifconfig
desc: ''
updated: 1623965306192
created: 1623965306192
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ifconfig

> Network Interface Configurator.

- View network settings of an ethernet adapter:

`ifconfig eth0`

- Display details of all interfaces, including disabled interfaces:

`ifconfig -a`

- Disable eth0 interface:

`ifconfig eth0 down`

- Enable eth0 interface:

`ifconfig eth0 up`

- Assign IP address to eth0 interface:

`ifconfig eth0 {{ip_address}}`

