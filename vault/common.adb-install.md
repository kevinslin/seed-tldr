---
id: common.adb-install
title: Adb Install
desc: ''
updated: 1623965016111
created: 1623965016111
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# adb install

> Android Debug Bridge Install: Push packages to an Android emulator instance or connected Android devices.
> More information: <https://developer.android.com/studio/command-line/adb>.

- Push an Android application to an emulator/device:

`adb install {{path/to/file.apk}}`

- Reinstall an existing app, keeping its data:

`adb install -r {{path/to/file.apk}}`

- Grant all permissions listed in the app manifest:

`adb install -g {{path/to/file.apk}}`

- Quickly update an installed package by only updating the parts of the APK that changed:

`adb install --fastdeploy {{path/to/file.apk}}`

