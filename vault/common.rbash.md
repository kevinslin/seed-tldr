---
id: common.rbash
title: Rbash
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rbash

> Restricted Bash shell.
> Similar to the `bash` shell with some restrictions like changing directories with `cd`, setting/unsetting of PATH, ENV variables and others.

- Start rbash:

`rbash`

- Execute a command:

`rbash -c "{{command}}"`

- Run commands from a file:

`rbash {{file.sh}}`

- Print the version information of rbash:

`rbash --version`

