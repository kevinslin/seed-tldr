---
id: common.termdown
title: Termdown
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# termdown

> Countdown timer and stopwatch for the command-line.
> More information: <https://github.com/trehn/termdown>.

- Start a stopwatch:

`termdown`

- Start a 1 minute and 30 seconds countdown:

`termdown {{1m30s}}`

- Start a 1 minute 30 seconds countdown with blinking the terminal at the end:

`termdown {{1m30s}} --blink`

- Show a title above countdown:

`termdown {{1m30s}} --title "{{Interesting title}}"`

- Display current time:

`termdown --time`

