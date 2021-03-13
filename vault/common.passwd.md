---
id: common.passwd
title: Passwd
desc: ''
updated: 1615663978728
created: 1615663978728
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# passwd

> Passwd is a tool used to change a user's password.

- Change the password of the current user interactively:

`passwd`

- Change the password of the current user:

`passwd {{new_password}}`

- Change the password of the specified user:

`passwd {{username}} {{new_password}}`

- Get the current status of the user:

`passwd -S`

- Make the password of the account blank (it will set the named account passwordless):

`passwd -d`

