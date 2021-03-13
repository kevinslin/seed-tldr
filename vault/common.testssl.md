---
id: common.testssl
title: Testssl
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# testssl

> Check SSL/TLS protocols and ciphers supported by a server.
> More information: <https://testssl.sh/>.

- Test a server (run every check) on port 443:

`testssl {{example.com}}`

- Test a different port:

`testssl {{example.com:465}}`

- Only check available protocols:

`testssl --protocols {{example.com}}`

- Only check vulnerabilities:

`testssl --vulnerable {{example.com}}`

- Only check HTTP security headers:

`testssl --headers {{example.com}}`

