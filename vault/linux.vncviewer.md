---
id: linux.vncviewer
title: Vncviewer
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vncviewer

> Launches a VNC (Virtual Network Computing) client.

- Launch a VNC client which connects to a host on a given display:

`vncviewer {{host}}:{{display_number}}`

- Launch in full-screen mode:

`vncviewer -FullScreen {{host}}:{{display_number}}`

- Launch a VNC client with a specific screen geometry:

`vncviewer --geometry {{width}}x{{height}} {{host}}:{{display_number}}`

- Launch a VNC client which connects to a host on a given port:

`vncviewer {{host}}::{{port}}`

