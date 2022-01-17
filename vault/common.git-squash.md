---
id: common.git-squash
title: Git Squash
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
# git squash

> Squash multiple commits into a single commit.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-squash>.

- Merge all commits from a specific branch into the current branch as a single commit:

`git squash {{source_branch}}`

- Squash all commits starting with a specific commit on the current branch:

`git squash {{commit}}`

- Squash the `n` latest commits and commit with a message:

`git squash HEAD~{{n}} "{{message}}"`

- Squash the `n` latest commits and commit concatenating all individual messages:

`git squash --squash-msg HEAD~{{n}}`

