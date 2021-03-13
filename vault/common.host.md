---
id: common.host
title: Host
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# host

> Lookup Domain Name Server.

- Lookup A, AAAA, and MX records of a domain:

`host {{domain}}`

- Lookup a field (CNAME, TXT,...) of a domain:

`host -t {{field}} {{domain}}`

- Reverse lookup an IP:

`host {{ip_address}}`

- Specify an alternate DNS server to query:

`host {{domain}} {{8.8.8.8}}`

