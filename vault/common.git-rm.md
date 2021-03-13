---
id: common.git-rm
title: Git Rm
desc: ''
updated: 1615663978714
created: 1615663978714
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git rm

> Remove files from repository index and local filesystem.
> More information: <https://git-scm.com/docs/git-rm>.

- Remove file from repository index and filesystem:

`git rm {{file}}`

- Remove directory:

`git rm -r {{directory}}`

- Remove file from repository index but keep it untouched locally:

`git rm --cached {{file}}`

