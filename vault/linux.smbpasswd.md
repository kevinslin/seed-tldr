---
id: linux.smbpasswd
title: Smbpasswd
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

