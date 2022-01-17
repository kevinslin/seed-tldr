---
id: common.git-coauthor
title: Git Coauthor
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
# git coauthor

> Add another author to the latest commit. Since this command rewrites the Git history, `--force` will be needed when pushing next time.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-coauthor>.

- Insert an additional author to the last Git commit:

`git coauthor {{name}} {{name@example.com}}`

