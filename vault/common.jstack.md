---
id: common.jstack
title: Jstack
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# jstack

> Java Stack Trace Tool.

- Print java stack traces for all threads in a java process:

`jstack {{java_pid}}`

- Print mixed mode (java/c++) stack traces for all threads in a java process:

`jstack -m {{java_pid}}`

- Print stack traces from java core dump:

`jstack {{/usr/bin/java}} {{file.core}}`

