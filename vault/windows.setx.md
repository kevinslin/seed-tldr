---
id: windows.setx
title: Setx
desc: ''
updated: 1642441815129
created: 1642441815129
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# setx

> Sets persistent environment variables.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/setx>.

- Set an environment variable for the current user:

`setx {{variable}} {{value}}`

- Set an environment variable for the current machine:

`setx {{variable}} {{value}} /M`

- Set an environment variable for a user on a remote machine:

`setx /s {{hostname}} /u {{username}} /p {{password}} {{variable}} {{value}}`

- Set an environment variable from a registry key value:

`setx {{variable}} /k {{registry\key\path}}`

