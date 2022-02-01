---
id: common.git-revert
title: Git Revert
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
# git revert

> Create new commits which reverse the effect of earlier ones.
> More information: <https://git-scm.com/docs/git-revert>.

- Revert the most recent commit:

`git revert {{HEAD}}`

- Revert the 5th last commit:

`git revert HEAD~{{4}}`

- Revert multiple commits:

`git revert {{branch_name~5..branch_name~2}}`

- Don't create new commits, just change the working tree:

`git revert -n {{0c01a9..9a1743}}`

