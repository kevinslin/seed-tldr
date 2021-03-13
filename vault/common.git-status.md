---
id: common.git-status
title: Git Status
desc: ''
updated: 1615663978714
created: 1615663978714
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git status

> Show the changes to files in a Git repository.
> Lists changed, added and deleted files compared to the currently checked-out commit.
> More information: <https://git-scm.com/docs/git-status>.

- Show changed files which are not yet added for commit:

`git status`

- Give output in [s]hort format:

`git status -s`

- Don't show untracked files in the output:

`git status --untracked-files=no`

- Show output in [s]hort format along with [b]ranch info:

`git status -sb`

