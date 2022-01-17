---
id: common.git-lock
title: Git Lock
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git lock

> Lock a file in a Git repository from being modified by a commit.
> Part of `git-extras`. See also `git-unlock`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-lock>.

- Disable the ability to commit changes of a local file:

`git lock {{path/to/file}}`

