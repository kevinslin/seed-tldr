---
id: linux.x0vncserver
title: X0vncserver
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# x0vncserver

> TigerVNC Server for X displays.
> More information: <https://tigervnc.org/doc/x0vncserver.html>.

- Start a VNC server using a passwordfile:

`x0vncserver -display {{:0}} -passwordfile {{path/to/file}}`

- Start a VNC server using a specific port:

`x0vncserver -display {{:0}} -rfbport {{port}}`

