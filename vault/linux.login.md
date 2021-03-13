---
id: linux.login
title: Login
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# login

> Initiates a session for a user.

- Login as a user:

`login {{user}}`

- Login as user without authentication if user is preauthenticated:

`login -f {{user}}`

- Login as user and preserve environment:

`login -p {{user}}`

- Login as a user on a remote host:

`login -h {{host}} {{user}}`

