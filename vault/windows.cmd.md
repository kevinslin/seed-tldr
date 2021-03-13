---
id: windows.cmd
title: Cmd
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cmd

> The Windows command interpreter.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- Start a new instance of the command interpreter:

`cmd`

- Run the specified command and then exit:

`cmd /c "{{command}}"`

- Run the specified command and then enter an interactive shell:

`cmd /k "{{command}}"`

- Disable the usage of `echo` in command output:

`cmd /q`

- Enable or disable command extensions:

`cmd /e:{{on|off}}`

- Enable or disable file or directory autocompletion:

`cmd /f:{{on|off}}`

- Enable or disable environment variable expansion:

`cmd /v:{{on|off}}`

- Force output to use unicode encoding:

`cmd /u`

