---
id: common.git-switch
title: Git Switch
desc: ''
updated: 1642441815027
created: 1642441815027
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git switch

> Switch between Git branches. Requires Git version 2.23+.
> See also `git checkout`.
> More information: <https://git-scm.com/docs/git-switch>.

- Switch to an existing branch:

`git switch {{branch_name}}`

- Create a new branch and switch to it:

`git switch --create {{branch_name}}`

- Create a new branch based on an existing commit and switch to it:

`git switch --create {{branch_name}} {{commit}}`

- Switch to the previous branch:

`git switch -`

- Switch to a branch and update all submodules to match:

`git switch --recurse-submodules {{branch_name}}`

- Switch to a branch and automatically merge the current branch and any uncommitted changes into it:

`git switch --merge {{branch_name}}`

