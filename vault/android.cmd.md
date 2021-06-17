---
id: android.cmd
title: Cmd
desc: ''
updated: 1623965306171
created: 1623965306171
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmd

> Android service manager.
> More information: <https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/cmd/>.

- List every running service:

`cmd -l`

- Call a specific service:

`cmd {{alarm}}`

- Call a service with arguments:

`cmd {{vibrator}} {{vibrate 300}}`

