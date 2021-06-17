---
id: common.jstack
title: Jstack
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jstack

> Java Stack Trace Tool.

- Print java stack traces for all threads in a java process:

`jstack {{java_pid}}`

- Print mixed mode (java/c++) stack traces for all threads in a java process:

`jstack -m {{java_pid}}`

- Print stack traces from java core dump:

`jstack {{/usr/bin/java}} {{file.core}}`

