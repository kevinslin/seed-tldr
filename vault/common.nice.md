---
id: common.nice
title: Nice
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
# nice

> Execute a program with a custom scheduling priority (niceness).
> Niceness values range from -20 (the highest priority) to 19 (the lowest).
> More information: <https://www.gnu.org/software/coreutils/nice>.

- Launch a program with altered priority:

`nice -n {{niceness_value}} {{command}}`

