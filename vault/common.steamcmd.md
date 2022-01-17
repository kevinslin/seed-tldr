---
id: common.steamcmd
title: Steamcmd
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# steamcmd

> A command-line version of the Steam client.
> More information: <https://manned.org/steamcmd>.

- Install or update an application anonymously:

`steamcmd +login {{anonymous}} +app_update {{appid}} +quit`

- Install or update an application using the specified credentials:

`steamcmd +login {{username}} +app_update {{appid}} +quit`

- Install an application for a specific platform:

`steamcmd +@sSteamCmdForcePlatformType {{windows}} +login {{anonymous}} +app_update {{appid}} validate +quit`

