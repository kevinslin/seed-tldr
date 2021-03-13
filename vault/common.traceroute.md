---
id: common.traceroute
title: Traceroute
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# traceroute

> Print the route packets trace to network host.

- Traceroute to a host:

`traceroute {{host}}`

- Disable IP address and host name mapping:

`traceroute -n {{host}}`

- Specify wait time for response:

`traceroute -w {{0.5}} {{host}}`

- Specify number of queries per hop:

`traceroute -q {{5}} {{host}}`

- Specify size in bytes of probing packet:

`traceroute {{host}} {{42}}`

