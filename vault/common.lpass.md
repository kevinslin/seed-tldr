---
id: common.lpass
title: Lpass
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lpass

> Command-line interface for the LastPass password manager.
> More information: <https://github.com/lastpass/lastpass-cli>.

- Log in to your LastPass account, by entering your master password when prompted:

`lpass login {{username}}`

- Show login status:

`lpass status`

- List all sites grouped by category:

`lpass ls`

- Generate a new password for gmail.com with the identifier `myinbox` and add to LastPass:

`lpass generate --username {{username}} --url {{gmail.com}} {{myinbox}} {{password_length}}`

- Show password for a specified entry:

`lpass show {{myinbox}} --password`

