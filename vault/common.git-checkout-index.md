---
id: common.git-checkout-index
title: Git Checkout Index
desc: ''
updated: 1623965306186
created: 1623965306186
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git checkout-index

> Copy files from the index to the working tree.
> More information: <https://git-scm.com/docs/git-checkout-index>.

- Restore any files deleted since the last commit:

`git checkout-index --all`

- Restore any files deleted or changed since the last commit:

`git checkout-index --all --force`

- Restore any files changed since the last commit, ignoring any files that were deleted:

`git checkout-index --all --force --no-create`

- Export a copy of the entire tree at the last commit to the specified directory (the trailing slash is important):

`git checkout-index --all --force --prefix={{path/to/export_directory/}}`

