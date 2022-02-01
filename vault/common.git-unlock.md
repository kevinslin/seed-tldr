---
id: common.git-unlock
title: Git Unlock
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
# git unlock

> Unlock a file in a Git repository so it can be modified by a commit.
> Part of `git-extras`. See also `git lock`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-unlock>.

- Enable the ability to commit changes of a previously-locked local file:

`git unlock {{path/to/file}}`

