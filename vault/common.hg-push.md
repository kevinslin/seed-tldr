---
id: common.hg-push
title: Hg Push
desc: ''
updated: 1615655543062
created: 1615655543062
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# hg push

> Push changes from the local repository to a specified destination.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#push>.

- Push changes to the "default" remote path:

`hg push`

- Push changes to a specified remote repository:

`hg push {{path/to/destination_repository}}`

- Push a new branch if it does not exist (disabled by default):

`hg push --new-branch`

- Specify a specific revision changeset to push:

`hg push --rev {{revision}}`

- Specify a specific branch to push:

`hg push --branch {{branch}}`

- Specify a specific bookmark to push:

`hg push --bookmark {{bookmark}}`

