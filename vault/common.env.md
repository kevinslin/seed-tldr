---
id: common.env
title: Env
desc: ''
updated: 1615655543053
created: 1615655543053
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# env

> Show the environment or run a program in a modified environment.

- Show the environment:

`env`

- Run a program. Often used in scripts after the shebang (#!) for looking up the path to the program:

`env {{program}}`

- Clear the environment and run a program:

`env -i {{program}}`

- Remove variable from the environment and run a program:

`env -u {{variable}} {{program}}`

- Set a variable and run a program:

`env {{variable}}={{value}} {{program}}`

- Set multiple variables and run a program:

`env {{variable1}}={{value}} {{variable2}}={{value}} {{variable3}}={{value}} {{program}}`

