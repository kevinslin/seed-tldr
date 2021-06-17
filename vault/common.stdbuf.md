---
id: common.stdbuf
title: Stdbuf
desc: ''
updated: 1623965016151
created: 1623965016151
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stdbuf

> Run a command with modified buffering operations for its standard streams.
> More information: <https://www.gnu.org/software/coreutils/stdbuf>.

- Change the standard input buffer size to 512 KiB:

`stdbuf --input={{512K}} {{command}}`

- Change the standard output buffer to line-buffered:

`stdbuf --output={{L}} {{command}}`

- Change the standard error buffer to unbuffered:

`stdbuf --error={{0}} {{command}}`

