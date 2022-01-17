---
id: common.testssl
title: Testssl
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

