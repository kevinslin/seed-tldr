---
id: android.logcat
title: Logcat
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
# logcat

> Dump a log of system messages.
> More information: <https://developer.android.com/studio/command-line/logcat>.

- Display system logs:

`logcat`

- Write system logs to a file:

`logcat -f {{path/to/file}}`

- Display lines that match a regular expression:

`logcat --regex {{regular_expression}}`

