---
id: osx.apachectl
title: Apachectl
desc: ''
updated: 1623965016172
created: 1623965016172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apachectl

> Apache HTTP Server control interface for macOS.

- Start the `org.apache.httpd` launchd job:

`apachectl start`

- Stop the launchd job:

`apachectl stop`

- Stop, then start launchd job:

`apachectl restart`

