---
id: common.ffsend
title: Ffsend
desc: ''
updated: 1615655543054
created: 1615655543054
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ffsend

> Easily and securely share files from command line.
> More information: <https://gitlab.com/timvisee/ffsend>.

- Upload a file:

`ffsend upload {{file}}`

- Download a file:

`ffsend download {{url}}`

- Upload a file with password:

`ffsend upload {{file}} -p {{password}}`

- Download a file protected by password:

`ffsend download {{file}} -p {{password}}`

- Upload a file and allow 4 downloads:

`ffsend upload {{file}} -d {{4}}`

