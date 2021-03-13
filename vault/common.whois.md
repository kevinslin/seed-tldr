---
id: common.whois
title: Whois
desc: ''
updated: 1615655543093
created: 1615655543093
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# whois

> Commandline client for the WHOIS (RFC 3912) protocol.
> More information: <https://github.com/rfc1036/whois>.

- Get information about a domain name:

`whois {{example.com}}`

- Get information about an IP address:

`whois {{8.8.8.8}}`

- Get abuse contact for an IP address:

`whois -b {{8.8.8.8}}`

