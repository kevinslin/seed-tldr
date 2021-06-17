---
id: common.adb-reverse
title: Adb Reverse
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
# adb reverse

> Android Debug Bridge Reverse: reverse socket connections from an Android emulator instance or connected Android devices.
> More information: <https://developer.android.com/studio/command-line/adb>.

- List all reverse socket connections from emulators and devices:

`adb reverse --list`

- Reverse a TCP port from an emulator or device to localhost:

`adb reverse tcp:{{remote_port}} tcp:{{local_port}}`

- Remove a reverse socket connections from an emulator or device:

`adb reverse --remove tcp:{{remote_port}}`

- Remove all reverse socket connections from all emulators and devices:

`adb reverse --remove-all`

