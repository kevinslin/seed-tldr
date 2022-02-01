---
id: windows.logoff
title: Logoff
desc: ''
updated: 1642441815128
created: 1642441815128
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logoff

> Terminate a login session.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/logoff>.

- Terminate the current session:

`logoff`

- Terminate a session by its name or id:

`logoff {{session_name|session_id}}`

- Terminate a session on a specific server connected through RDP:

`logoff {{session_name|session_id}} /server:{{servername}}`

