---
id: linux.pdbedit
title: Pdbedit
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdbedit

> Edit the Samba user database.
> For simple user add/remove/password, you can also use `smbpasswd`.
> More information: <https://manned.org/pdbedit>.

- List all Samba users (use verbose flag to show their settings):

`sudo pdbedit --list --verbose`

- Add an existing Unix user to Samba (will prompt for password):

`sudo pdbedit --user {{username}} --create`

- Remove a Samba user:

`sudo pdbedit --user {{username}} --delete`

- Reset a Samba user's failed password counter:

`sudo pdbedit --user {{username}} --bad-password-count-reset`

