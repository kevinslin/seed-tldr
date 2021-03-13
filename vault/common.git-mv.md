---
id: common.git-mv
title: Git Mv
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git mv

> Move or rename files and update the Git index.
> More information: <https://git-scm.com/docs/git-mv>.

- Move file inside the repo and add the movement to the next commit:

`git mv {{path/to/file}} {{new/path/to/file}}`

- Rename file and add renaming to the next commit:

`git mv {{filename}} {{new_filename}}`

- Overwrite the file in the target path if it exists:

`git mv --force {{file}} {{target}}`

