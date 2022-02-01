---
id: common.git-add
title: Git Add
desc: ''
updated: 1642441815021
created: 1642441815021
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git add

> Adds changed files to the index.
> More information: <https://git-scm.com/docs/git-add>.

- Add a file to the index:

`git add {{path/to/file}}`

- Add all files (tracked and untracked):

`git add -A`

- Only add already tracked files:

`git add -u`

- Also add ignored files:

`git add -f`

- Interactively stage parts of files:

`git add -p`

- Interactively stage parts of a given file:

`git add -p {{path/to/file}}`

- Interactively stage a file:

`git add -i`

