---
id: common.aapt
title: Aapt
desc: ''
updated: 1642441814991
created: 1642441814991
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aapt

> Android Asset Packaging Tool.
> Compile and package an Android app's resources.
> More information: <https://elinux.org/Android_aapt>.

- List files contained in an APK archive:

`aapt list {{path/to/app.apk}}`

- Display an app's metadata (version, permissions, etc.):

`aapt dump badging {{path/to/app.apk}}`

- Create a new APK archive with files from the specified directory:

`aapt package -F {{path/to/app.apk}} {{path/to/directory}}`

