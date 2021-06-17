---
id: common.env
title: Env
desc: ''
updated: 1623965306183
created: 1623965306183
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# env

> Show the environment or run a program in a modified environment.
> More information: <https://www.gnu.org/software/coreutils/env>.

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

