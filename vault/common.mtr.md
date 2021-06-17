---
id: common.mtr
title: Mtr
desc: ''
updated: 1623965016137
created: 1623965016137
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mtr

> Matt's Traceroute: combined traceroute and ping tool.
> More information: <https://bitwizard.nl/mtr>.

- Traceroute to a host and continuously ping all intermediary hops:

`mtr {{host}}`

- Disable IP address and host name mapping:

`mtr -n {{host}}`

- Generate output after pinging each hop 10 times:

`mtr -w {{host}}`

- Force IP IPv4 or IPV6:

`mtr -4 {{host}}`

- Wait for a given time (in seconds) before sending another packet to the same hop:

`mtr -i {{seconds}} {{host}}`

