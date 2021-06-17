---
id: linux.nologin
title: Nologin
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nologin

> Alternative shell that prevents a user from logging in.

- Set a user's login shell to `nologin` to prevent the user from logging in:

`chsh -s {{user}} nologin`

- Customize message for users with the login shell of `nologin`:

`echo "{{declined_login_message}}" > /etc/nologin.txt`

