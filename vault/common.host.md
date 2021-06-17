---
id: common.host
title: Host
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

