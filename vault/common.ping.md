---
id: common.ping
title: Ping
desc: ''
updated: 1615655543078
created: 1615655543078
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ping

> Send ICMP ECHO_REQUEST packets to network hosts.

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

