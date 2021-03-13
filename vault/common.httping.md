---
id: common.httping
title: Httping
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# httping

> Measure the latency and throughput of a web server.
> More information: <https://www.vanheusden.com/httping>.

- Ping the specified url:

`httping -g {{url}}`

- Ping the web server on `host` and `port`:

`httping -h {{host}} -p {{port}}`

- Ping the web server on `host` using a TLS connection:

`httping -l -g https://{{host}}`

- Ping the web server on `host` using HTTP basic authentication:

`httping -g http://{{host}} -U {{username}} -P {{password}}`

