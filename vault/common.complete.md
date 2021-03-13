---
id: common.complete
title: Complete
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# complete

> Provides argument autocompletion to shell commands.

- Apply a function that performs autocompletion to a command:

`complete -F {{function}} {{command}}`

- Apply a command that performs autocompletion to another command:

`complete -C {{autocomplete_command}} {{command}}`

- Apply autocompletion without appending a space to the completed word:

`complete -o nospace -F {{function}} {{command}}`

