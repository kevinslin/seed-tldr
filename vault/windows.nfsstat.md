---
id: windows.nfsstat
title: Nfsstat
desc: ''
updated: 1623965306238
created: 1623965306238
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nfsstat

> Display or reset the number of calls made to the NFS server.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/nfsstat>.

- Display the recorded number of calls made to the NFS server:

`nfsstat`

- Reset the recorded number of calls made to the NFS server:

`nfsstat -z`

