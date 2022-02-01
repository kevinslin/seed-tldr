---
id: windows.query
title: Query
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
# query

> Displays information about user sessions and process.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/query>.

- Display all user sessions:

`query session`

- Display the current user sessions on a remote computer:

`query session /server:{{hostname}}`

- Display logged in users:

`query user`

- Display all user sessions on a remote computer:

`query session /server:{{hostname}}`

- Display all running processes:

`query process`

- Display running processes by session or user name:

`query process {{session_name|user_name}}`

