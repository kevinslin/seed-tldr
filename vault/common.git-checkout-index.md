---
id: common.git-checkout-index
title: Git Checkout Index
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

