---
id: windows.set
title: Set
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# set

> Display or set environment variables for the current instance of CMD.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/set>.

- List all current environment variables:

`set`

- Set an environment variable to a specific value:

`set {{name}}={{value}}`

- List environment variables starting with the specified string:

`set {{name}}`

- Prompt the user for a value for the specified variable:

`set /p {{name}}={{prompt_string}}`

