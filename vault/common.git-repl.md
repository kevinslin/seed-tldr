---
id: common.git-repl
title: Git Repl
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git repl

> Git REPL (read-evaluate-print-loop) - an interactive Git shell.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-repl>.

- Start an interactive Git shell:

`git repl`

- Run a Git command while in the interactive Git shell:

`{{git_subcommand}} {{command_arguments}}`

- Run an external (non-Git) command while in the interactive Git shell:

`!{{command}} {{command_arguments}}`

- Exit the interactive Git shell (or press Ctrl + D):

`exit`

