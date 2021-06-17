---
id: linux.gpasswd
title: Gpasswd
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gpasswd

> Administer `/etc/group` and `/etc/gshadow`.

- Define group administrators:

`sudo gpasswd -A {{user1,user2}} {{group}}`

- Set the list of group members:

`sudo gpasswd -M {{user1,user2}} {{group}}`

- Create a password for the named group:

`gpasswd {{group}}`

- Add a user to the named group:

`gpasswd -a {{user}} {{group}}`

- Remove a user from the named group:

`gpasswd -d {{user}} {{group}}`

