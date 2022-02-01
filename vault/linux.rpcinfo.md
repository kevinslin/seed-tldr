---
id: linux.rpcinfo
title: Rpcinfo
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rpcinfo

> Makes an RPC call to an RPC server and reports what it finds.

- Show full table of all RPC services registered on localhost:

`rpcinfo`

- Show concise table of all RPC services registered on localhost:

`rpcinfo -s {{localhost}}`

- Display table of statistics of rpcbind operations on localhost:

`rpcinfo -m`

- Display list of entries of given service name (mountd) and version number (2) on a remote nfs share:

`rpcinfo -l {{remote_nfs_server_ip}} {{mountd}} {{2}}`

- Delete the registration for version 1 of the mountd service for all transports:

`rpcinfo -d {{mountd}} {{1}}`

