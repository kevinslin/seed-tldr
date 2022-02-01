---
id: linux.x0vncserver
title: X0vncserver
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
# x0vncserver

> TigerVNC Server for X displays.
> More information: <https://tigervnc.org/doc/x0vncserver.html>.

- Start a VNC server using a passwordfile:

`x0vncserver -display {{:0}} -passwordfile {{path/to/file}}`

- Start a VNC server using a specific port:

`x0vncserver -display {{:0}} -rfbport {{port}}`

