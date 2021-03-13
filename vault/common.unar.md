---
id: common.unar
title: Unar
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# unar

> Extract contents from archive files.

- Extract an archive to the current directory:

`unar {{archive}}`

- Extract an archive to the specified directory:

`unar -o {{path/to/directory}} {{archive}}`

- Force overwrite if files to be unpacked already exist:

`unar -f {{archive}}`

- Force rename if files to be unpacked already exist:

`unar -r {{archive}}`

- Force skip if files to be unpacked already exist:

`unar -s {{archive}}`

