---
id: android.bugreportz
title: Bugreportz
desc: ''
updated: 1642441814990
created: 1642441814990
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bugreportz

> Generate a zipped Android bug report.
> This command can only be used through `adb shell`.
> More information: <https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/bugreportz>.

- Generate a complete zipped bug report of an Android device:

`bugreportz`

- Show the progress of a running `bugreportz` operation:

`bugreportz -p`

- Show the version of `bugreportz`:

`bugreportz -v`

- Display help:

`bugreportz -h`

