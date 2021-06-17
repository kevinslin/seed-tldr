---
id: common.git-pr
title: Git Pr
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
# git pr

> Check out GitHub pull requests locally.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-pr>.

- Check out a specific pull request:

`git pr {{pr_number}}`

- Check out a pull request for a specific remote:

`git pr {{pr_number}} {{remote}}`

- Check out a pull request from its URL:

`git pr {{url}}`

- Clean up old pull request branches:

`git pr clean`

