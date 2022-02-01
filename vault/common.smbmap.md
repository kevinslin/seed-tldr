---
id: common.smbmap
title: Smbmap
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smbmap

> Allow users to enumerate samba share drives across an entire domain.
> More information: <https://github.com/ShawnDEvans/smbmap>.

- Enumerate hosts with NULL sessions enabled and open shares:

`smbmap --host-file {{path/to/file}}`

- Enumerate hosts and check SMB file permissions:

`smbmap --host-file {{path/to/file}} -u {{username}} -p {{password}} -q`

- Connect to an ip or hostname through smb using a username and password:

`smbmap -u {{username}} -p {{password}} -d {{domain}} -H {{ip_or_hostname}}`

- Locate and download files [R]ecursively up to N levels depth, searching for filename pattern (regex), and excluding certain shares:

`smbmap --host-file {{path/to/file}} -u {{username}} -p {{password}} -q -R --depth {{number}} --exclude {{sharename}} -A {{filepattern}}`

- Upload file through smb using username and password:

`smbmap -u {{username}} -p {{password}} -d {{domain}} -H {{ip_or_hostname}} --upload {{path/to/file}} '{{/share_name/remote_filename}}'`

