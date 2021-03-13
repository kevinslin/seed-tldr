---
id: linux.eval
title: Eval
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# eval

> Execute arguments as a single command in the current shell and return its result.

- Call `echo` with the "foo" argument:

`eval "{{echo foo}}"`

- Set a variable in the current shell:

`eval "{{foo=bar}}"`

