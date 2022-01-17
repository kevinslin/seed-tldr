---
id: osx.launchd
title: Launchd
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# launchd

> This manages processes, both for the system and users.
> You cannot invoke launchd manually, use launchctl to interact with it.
> More information: <https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/Introduction.html>.

- Run init:

`/sbin/launchd`

- View documentation for interacting with launchd using launchctl:

`tldr launchctl`

