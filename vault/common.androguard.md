---
id: common.androguard
title: Androguard
desc: ''
updated: 1642441814993
created: 1642441814993
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# androguard

> Reverse engineering tool for Android applications. Written in Python.
> More information: <https://github.com/androguard/androguard>.

- Display Android app manifest:

`androguard axml {{path/to/app.apk}}`

- Display app metadata (version and app ID):

`androguard apkid {{path/to/app.apk}}`

- Decompile Java code from an app:

`androguard decompile {{path/to/app.apk}} --output {{path/to/directory}}`

