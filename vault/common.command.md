---
id: common.command
title: Command
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# command

> Command forces the shell to execute the program and ignore any functions, builtins and aliases with the same name.

- Execute the `ls` program literally, even if an `ls` alias exists:

`command {{ls}}`

- Display the path to the executable or the alias definition of a specific command:

`command -v {{command_name}}`

