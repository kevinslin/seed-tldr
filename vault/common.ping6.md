---
id: common.ping6
title: Ping6
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ping6

> Send ICMP ECHO_REQUEST packets to network hosts via IPv6 address.

- Ping a host:

`ping6 {{host}}`

- Ping a host only a specific number of times:

`ping6 -c {{count}} {{host}}`

- Ping a host, specifying the interval in seconds between requests (default is 1 second):

`ping6 -i {{seconds}} {{host}}`

- Ping a host without trying to lookup symbolic names for addresses:

`ping6 -n {{host}}`

- Ping a host and ring the bell when a packet is received (if your terminal supports it):

`ping6 -a {{host}}`

