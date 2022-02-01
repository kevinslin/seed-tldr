---
id: common.passwd
title: Passwd
desc: ''
updated: 1642441815055
created: 1642441815055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# passwd

> Passwd is a tool used to change a user's password.
> More information: <https://manned.org/passwd>.

- Change the password of the current user interactively:

`passwd`

- Change the password of a specific user:

`passwd {{username}}`

- Get the current status of the user:

`passwd -S`

- Make the password of the account blank (it will set the named account passwordless):

`passwd -d`

