---
id: common.git-diff-files
title: Git Diff Files
desc: ''
updated: 1642441815023
created: 1642441815023
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git diff-files

> Compare files using their sha1 hashes and modes.
> More information: <https://git-scm.com/docs/git-diff-files>.

- Compare all changed files:

`git diff-files`

- Compare only specified files:

`git diff-files {{path/to/file}}`

- Show only the names of changed files:

`git diff-files --name-only`

- Output a summary of extended header information:

`git diff-files --summary`

