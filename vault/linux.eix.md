---
id: linux.eix
title: Eix
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# eix

> Utilities for searching local Gentoo packages.
> Update local package cache using `eix-update`.

- Search for a package:

`eix {{package_name}}`

- Search for installed packages:

`eix --installed {{package_name}}`

- Search in package descriptions:

`eix --description "{{description}}"`

- Search by package license:

`eix --license {{license}}`

- Exclude results from search:

`eix --not --license {{license}}`

