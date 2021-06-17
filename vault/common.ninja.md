---
id: common.ninja
title: Ninja
desc: ''
updated: 1623965016139
created: 1623965016139
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ninja

> A Build system designed to be fast.
> More information: <https://ninja-build.org/manual.html>.

- Build in the current directory:

`ninja`

- Build a program in a given directory:

`ninja -C {{path/to/directory}}`

- Show targets (e.g. `install` and `uninstall`):

`ninja -t targets`

- Show help:

`ninja -h`

