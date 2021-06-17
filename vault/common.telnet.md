---
id: common.telnet
title: Telnet
desc: ''
updated: 1623965016152
created: 1623965016152
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# telnet

> Connect to a specified port of a host using the telnet protocol.

- Telnet to the default port of a host:

`telnet {{host}}`

- Telnet to a specific port of a host:

`telnet {{ip_address}} {{port}}`

- Exit a telnet session:

`quit`

- Emit the default escape character combination for terminating the session:

`Ctrl + ]`

- Start telnet with "x" as the session termination character:

`telnet -e {{x}} {{ip_address}} {{port}}`

- Telnet to Star Wars animation:

`telnet {{towel.blinkenlights.nl}}`

