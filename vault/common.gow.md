---
id: common.gow
title: Gow
desc: ''
updated: 1645783307329
created: 1645783307329
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gow

> Watches Go files and restarts the app on changes.
> More information: <https://github.com/mitranim/gow>.

- Start and watch the current directory:

`gow run .`

- Start the application with the specified arguments:

`gow run . {{argument1 argument2 ...}}`

- Watch subdirectories in verbose mode:

`gow -v -w={{path/to/directory1,path/to/directory2,...}} run .`

- Watch the specified file extensions:

`gow -e={{go,html}} run .`

- Display help:

`gow -h`

