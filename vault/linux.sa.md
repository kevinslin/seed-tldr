---
id: linux.sa
title: Sa
desc: ''
updated: 1642441815112
created: 1642441815112
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sa

> Summarizes accounting information. Part of the acct package.
> Shows commands called by users, including basic info on CPU time spent processing and I/O rates.

- Display executable invocations per user (username not displayed):

`sudo sa`

- Display executable invocations per user, showing responsible usernames:

`sudo sa --print-users`

- List resources used recently per user:

`sudo sa --user-summary`

