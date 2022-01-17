---
id: common.git-clear
title: Git Clear
desc: ''
updated: 1642441815022
created: 1642441815022
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git clear

> Clear a Git working directory as if it was freshly cloned with the current branch including files in `.gitignore`.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-clear>.

- Reset all tracked files and delete all untracked files even if they are included in the `.gitignore`:

`git clear`

