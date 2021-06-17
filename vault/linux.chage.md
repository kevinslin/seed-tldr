---
id: linux.chage
title: Chage
desc: ''
updated: 1623965016159
created: 1623965016159
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chage

> Change user account and password expiry information.

- List password information for the user:

`chage -l {{username}}`

- Enable password expiration in 10 days:

`sudo chage -M {{10}} {{username}}`

- Disable password expiration:

`sudo chage -M -1 {{username}}`

- Set account expiration date:

`sudo chage -E {{YYYY-MM-DD}}`

- Force user to change password on next log in:

`sudo chage -d 0`

