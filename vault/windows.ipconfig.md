---
id: windows.ipconfig
title: Ipconfig
desc: ''
updated: 1623965016177
created: 1623965016177
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipconfig

> Display and manage the network configuration of Windows.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/ipconfig>.

- Show a list of network adapters:

`ipconfig`

- Show a detailed list of network adapters:

`ipconfig /all`

- Renew the IP addresses for a network adapter:

`ipconfig /renew {{adapter}}`

- Free up the IP addresses for a network adapter:

`ipconfig /release {{adapter}}`

- Remove all data from the DNS cache:

`ipconfig /flushdns`

