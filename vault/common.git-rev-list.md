---
id: common.git-rev-list
title: Git Rev List
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
# git rev-list

> List revisions (commits) in reverse chronological order.
> More information: <https://git-scm.com/docs/git-rev-list>.

- List all commits on the current branch:

`git rev-list {{HEAD}}`

- List commits more recent than a specific date, on a specific branch:

`git rev-list --since={{'2019-12-01 00:00:00'}} {{branch_name}}`

- List all merge commits on a specific commit:

`git rev-list --merges {{commit}}`

