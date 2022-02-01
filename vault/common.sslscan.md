---
id: common.sslscan
title: Sslscan
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sslscan

> Check SSL/TLS protocols and ciphers supported by a server.
> More information: <https://github.com/rbsec/sslscan>.

- Test a server on port 443:

`sslscan {{example.com}}`

- Test a specified port:

`sslscan {{example.com}}:{{465}}`

- Show certificate information:

`testssl --show-certificate {{example.com}}`

