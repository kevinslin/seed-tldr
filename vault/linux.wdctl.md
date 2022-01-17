---
id: linux.wdctl
title: Wdctl
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wdctl

> Show the hardware watchdog status.
> More information: <https://manned.org/wdctl>.

- Display the watchdog status:

`wdctl`

- Display the watchdog status in a single line in key-value pairs:

`wdctl --oneline`

- Display only specific watchdog flags (list is driver specific):

`wdctl --flags {{flag_list}}`

