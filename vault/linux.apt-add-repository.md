---
id: linux.apt-add-repository
title: Apt Add Repository
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# apt-add-repository

> Manages apt repository definitions.

- Add a new apt repository:

`apt-add-repository {{repository_spec}}`

- Remove an apt repository:

`apt-add-repository --remove {{repository_spec}}`

- Update the package cache after adding a repository:

`apt-add-repository --update {{repository_spec}}`

- Enable source packages:

`apt-add-repository --enable-source {{repository_spec}}`

