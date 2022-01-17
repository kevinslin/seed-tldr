---
id: common.git-pr
title: Git Pr
desc: ''
updated: 1642441815025
created: 1642441815025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git pr

> Check out GitHub pull requests locally.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-pr>.

- Check out a specific pull request:

`git pr {{pr_number}}`

- Check out a pull request from a specific remote:

`git pr {{pr_number}} {{remote}}`

- Check out a pull request from its URL:

`git pr {{url}}`

- Clean up old pull request branches:

`git pr clean`

