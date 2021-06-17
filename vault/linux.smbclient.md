---
id: linux.smbclient
title: Smbclient
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smbclient

> FTP-like client to access SMB/CIFS resources on servers.

- Connect to a share (user will be prompted for password; `exit` to quit the session):

`smbclient {{//server/share}}`

- Connect with a different username:

`smbclient {{//server/share}} --user {{username}}`

- Connect with a different workgroup:

`smbclient {{//server/share}} --workgroup {{domain}} --user {{username}}`

- Connect with a username and password:

`smbclient {{//server/share}} --user {{username%password}}`

- Download a file from the server:

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "get {{file.txt}}"`

- Upload a file to the server:

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "put {{file.txt}}"`

