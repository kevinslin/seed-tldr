---
id: android.pm
title: Pm
desc: ''
updated: 1623965016110
created: 1623965016110
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pm

> Show information about apps on an Android device.
> More information: <https://developer.android.com/studio/command-line/adb#pm>.

- Print a list of all installed apps:

`pm list packages`

- Print a list of all installed system apps:

`pm list packages -s`

- Print a list of all installed 3rd-Party apps:

`pm list packages -3`

- Print a list of apps matching specific keywords:

`pm list packages {{keywords}}`

- Print the path of the APK of a specific app:

`pm path {{app}}`

