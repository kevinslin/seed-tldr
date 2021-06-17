---
id: common.whois
title: Whois
desc: ''
updated: 1623965016155
created: 1623965016155
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# whois

> Command-line client for the WHOIS (RFC 3912) protocol.
> More information: <https://github.com/rfc1036/whois>.

- Get information about a domain name:

`whois {{example.com}}`

- Get information about an IP address:

`whois {{8.8.8.8}}`

- Get abuse contact for an IP address:

`whois -b {{8.8.8.8}}`

