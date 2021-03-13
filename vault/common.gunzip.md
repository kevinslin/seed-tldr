---
id: common.gunzip
title: Gunzip
desc: ''
updated: 1615655543062
created: 1615655543062
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gunzip

> Extract file(s) from a gzip (.gz) archive.

- Extract a file from an archive, replacing the original file if it exists:

`gunzip {{archive.tar.gz}}`

- Extract a file to a target destination:

`gunzip -c {{archive.tar.gz}} > {{archive.tar}}`

- List the contents of a compressed file:

`gunzip -l {{file.txt.gz}}`

