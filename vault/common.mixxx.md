---
id: common.mixxx
title: Mixxx
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mixxx

> Free and open source cross-platform DJ software.
> More information: <https://mixxx.org/manual/latest/chapters/appendix.html#command-line-options>.

- Start the Mixxx GUI in fullscreen:

`mixxx --fullScreen`

- Start in safe developer mode to debug a crash:

`mixxx --developer --safeMode`

- Debug a malfunction:

`mixxx --debugAssertBreak --developer --loglevel trace`

- Start mixxx using the specified settings file:

`mixxx --resourcePath {{mixxx/res/controllers}} --settingsPath {{path/to/settings-file}}`

- Debug a custom controller mapping:

`mixxx --controllerDebug --resourcePath {{path/to/mapping-directory}}`

- Show command-line help:

`mixxx --help`

