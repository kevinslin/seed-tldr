---
id: common.ping
title: Ping
desc: ''
updated: 1642441815058
created: 1642441815058
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ping

> Send ICMP ECHO_REQUEST packets to network hosts.
> More information: <https://manned.org/ping>.

- Ping host:

`ping {{host}}`

- Ping a host only a specific number of times:

`ping -c {{count}} {{host}}`

- Ping host, specifying the interval in seconds between requests (default is 1 second):

`ping -i {{seconds}} {{host}}`

- Ping host without trying to lookup symbolic names for addresses:

`ping -n {{host}}`

- Ping host and ring the bell when a packet is received (if your terminal supports it):

`ping -a {{host}}`

- Also display a message if no response was received:

`ping -O {{host}}`

