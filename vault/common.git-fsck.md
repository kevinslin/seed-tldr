---
id: common.git-fsck
title: Git Fsck
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git fsck

> Verify the validity and connectivity of nodes in a Git repository index.
> Does not make any modifications. See `git gc` for cleaning up dangling blobs.
> More information: <https://git-scm.com/docs/git-fsck>.

- Check the current repository:

`git fsck`

- List all tags found:

`git fsck --tags`

- List all root nodes found:

`git fsck --root`

