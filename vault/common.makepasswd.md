---
id: common.makepasswd
title: Makepasswd
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# makepasswd

> Generate and encrypt passwords.
> More information: <https://manpages.debian.org/stretch/makepasswd/makepasswd.1.en.html>.

- Generate a random password (8 to 10 characters long, containing letters and numbers):

`makepasswd`

- Generate a 10 characters long password:

`makepasswd --chars {{10}}`

- Generate a 5 to 10 characters long password:

`makepasswd --minchars {{5}} --maxchars {{10}}`

- Generate a password containing only the characters "b", "a" or "r":

`makepasswd --string {{bar}}`

