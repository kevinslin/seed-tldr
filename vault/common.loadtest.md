---
id: common.loadtest
title: Loadtest
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# loadtest

> Run a load test on the selected HTTP or WebSockets URL.
> More information: <https://github.com/alexfernandez/loadtest>.

- Run with concurrent users and a specified amount of requests per second:

`loadtest --concurrency {{10}} --rps {{200}} {{https://example.com}}`

- Run with a custom HTTP header:

`loadtest --headers "{{accept:text/plain;text-html}}" {{https://example.com}}`

- Run with a specific HTTP method:

`loadtest --method {{GET}} {{https://example.com}}`

