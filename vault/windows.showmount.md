---
id: windows.showmount
title: Showmount
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
# showmount

> Display information about NFS filesystems on Windows Server.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/showmount>.

- Display all exported filesystems:

`showmount -e`

- Display all NFS clients and their mounted directories:

`showmount -a`

- Display all NFS mounted directories:

`showmount -d`

- Display all exported filesystems for a remote server:

`showmount -e {{server_address}}`

