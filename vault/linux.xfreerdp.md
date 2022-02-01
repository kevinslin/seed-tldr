---
id: linux.xfreerdp
title: Xfreerdp
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xfreerdp

> Free Remote Desktop Protocol implementation.
> More information: <https://www.freerdp.com>.

- Connect to a FreeRDP server:

`xfreerdp /u:{{username}} /p:{{password}} /v:{{ip_address}}`

- Connect to a FreeRDP server and activate audio output redirection using `sys:alsa` device:

`xfreerdp /u:{{username}} /p:{{password}} /v:{{ip_address}} /sound:{{sys:alsa}}`

