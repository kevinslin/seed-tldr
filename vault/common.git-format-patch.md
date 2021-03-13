---
id: common.git-format-patch
title: Git Format Patch
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git format-patch

> Prepare .patch files. Useful when emailing commits elsewhere.
> See also `git am`, which can apply generated .patch files.
> More information: <https://git-scm.com/docs/git-format-patch>.

- Create an auto-named `.patch` file for all the unpushed commits:

`git format-patch {{origin}}`

- Write a `.patch` file for all the commits between 2 revisions to stdout:

`git format-patch {{revision_1}}..{{revision_2}}`

- Write a `.patch` file for the 3 latest commits:

`git format-patch -{{3}}`

