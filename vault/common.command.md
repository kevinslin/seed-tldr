---
id: common.command
title: Command
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# command

> Command forces the shell to execute the program and ignore any functions, builtins and aliases with the same name.
> More information: <https://manned.org/command>.

- Execute the `ls` program literally, even if an `ls` alias exists:

`command {{ls}}`

- Display the path to the executable or the alias definition of a specific command:

`command -v {{command_name}}`

