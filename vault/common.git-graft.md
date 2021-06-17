---
id: common.git-graft
title: Git Graft
desc: ''
updated: 1623965016127
created: 1623965016127
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git graft

> Merge commits from a specific branch into another branch and delete the source branch.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-graft>.

- Merge all commits not present on the target branch from the source branch to target branch, and delete the source branch:

`git graft {{source_branch}} {{target_branch}}`

