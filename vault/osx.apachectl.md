---
id: osx.apachectl
title: Apachectl
desc: ''
updated: 1642441815119
created: 1642441815119
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apachectl

> Apache HTTP Server control interface for macOS.
> More information: <https://www.unix.com/man-page/osx/8/apachectl/>.

- Start the `org.apache.httpd` launchd job:

`apachectl start`

- Stop the launchd job:

`apachectl stop`

- Stop, then start launchd job:

`apachectl restart`

