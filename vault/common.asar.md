---
id: common.asar
title: Asar
desc: ''
updated: 1615655543044
created: 1615655543044
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# asar

> A file archiver for the Electron platform.
> More information: <https://github.com/electron/asar>.

- Archive a file or directory:

`asar pack {{path/to/file_or_directory}} {{archived.asar}}`

- Extract an archive:

`asar extract {{archived.asar}}`

- Extract a specific file from an archive:

`asar extract-file {{archived.asar}} {{file}}`

- List the contents of an archive file:

`asar list {{archived.asar}}`

