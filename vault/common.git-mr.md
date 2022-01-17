---
id: common.git-mr
title: Git Mr
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
# git mr

> Check out GitLab merge requests locally.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-mr>.

- Check out a specific merge request:

`git mr {{mr_number}}`

- Check out a merge request from a specific remote:

`git mr {{mr_number}} {{remote}}`

- Checkout a merge request from its URL:

`git mr {{url}}`

- Clean up old merge request branches:

`git mr clean`

