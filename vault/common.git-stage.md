---
id: common.git-stage
title: Git Stage
desc: ''
updated: 1623965016128
created: 1623965016128
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git stage

> Add file contents to the staging area.
> Synonym of `git add`.
> More information: <https://git-scm.com/docs/git-stage>.

- Add a file to the index:

`git stage {{path/to/file}}`

- Add all files (tracked and untracked):

`git stage -A`

- Only add already tracked files:

`git stage -u`

- Also add ignored files:

`git stage -f`

- Interactively stage parts of files:

`git stage -p`

- Interactively stage parts of a given file:

`git stage -p {{path/to/file}}`

- Interactively stage a file:

`git stage -i`

