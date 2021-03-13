---
id: common.lpass
title: Lpass
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lpass

> Command line interface for the LastPass password manager.
> More information: <https://github.com/lastpass/lastpass-cli>.

- Login to your LastPass account, by entering your master password when prompted:

`lpass login {{username}}`

- Show login status:

`lpass status`

- List all sites grouped by category:

`lpass ls`

- Generate a new password for gmail.com with the identifier `myinbox` and add to LastPass:

`lpass generate --username {{username}} --url {{gmail.com}} {{myinbox}} {{password_length}}`

- Show password for a specified entry:

`lpass show {{myinbox}} --password`

