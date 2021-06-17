---
id: linux.smbpasswd
title: Smbpasswd
desc: ''
updated: 1623965016169
created: 1623965016169
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smbpasswd

> Change a user's SMB password.
> Samba users must also have a local Unix account.

- Change the current user's SMB password:

`smbpasswd`

- Add a specified user to Samba and set password(user should already exist in system):

`smbpasswd -a {{username}}`

- Modify an existing Samba user's password:

`smbpasswd {{username}}`

- Delete a Samba user:

`smbpasswd -x {{username}}`

