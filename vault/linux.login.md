---
id: linux.login
title: Login
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# login

> Initiates a session for a user.
> More information: <https://manned.org/login>.

- Log in as a user:

`login {{user}}`

- Log in as user without authentication if user is preauthenticated:

`login -f {{user}}`

- Log in as user and preserve environment:

`login -p {{user}}`

- Log in as a user on a remote host:

`login -h {{host}} {{user}}`

