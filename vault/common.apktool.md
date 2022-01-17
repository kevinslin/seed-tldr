---
id: common.apktool
title: Apktool
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apktool

> Reverse engineer APK files.
> More information: <https://ibotpeaches.github.io/Apktool/>.

- Decode an APK file:

`apktool d {{file.apk}}`

- Build an APK file from a directory:

`apktool b {{path/to/directory}}`

- Install and store frameworks:

`apktool if {{framework.apk}}`

