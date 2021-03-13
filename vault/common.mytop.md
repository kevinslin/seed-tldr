---
id: common.mytop
title: Mytop
desc: ''
updated: 1615655543072
created: 1615655543072
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mytop

> Display MySQL server performance info like `top`.
> More information: <http://www.mysqlfanboy.com/mytop-3>.

- Start mytop:

`mytop`

- Connect with a specified username and password:

`mytop -u {{user}} -p {{password}}`

- Connect with a specified username (the user will be prompted for a password):

`mytop -u {{user}} --prompt`

- Do not show any idle (sleeping) threads:

`mytop -u {{user}} -p {{password}} --noidle`

