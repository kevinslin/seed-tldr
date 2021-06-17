---
id: common.git-merge
title: Git Merge
desc: ''
updated: 1623965306188
created: 1623965306188
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git merge

> Merge branches.
> More information: <https://git-scm.com/docs/git-merge>.

- Merge a branch into your current branch:

`git merge {{branch_name}}`

- Edit the merge message:

`git merge -e {{branch_name}}`

- Merge a branch and create a merge commit:

`git merge --no-ff {{branch_name}}`

- Abort a merge in case of conflicts:

`git merge --abort`

