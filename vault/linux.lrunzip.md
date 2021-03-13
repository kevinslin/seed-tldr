---
id: linux.lrunzip
title: Lrunzip
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lrunzip

> A large file decompression program.
> See also `lrzip`, `lrztar`, `lrzuntar`.

- Decompress a file:

`lrunzip {{filename.lrz}}`

- Decompress a file using a specific number of processor threads:

`lrunzip -p {{8}} {{filename.lrz}}`

- Decompress a file and silently overwrite files if they exist:

`lrunzip -f {{filename.lrz}}`

- Keep broken or damaged files instead of deleting them when decompressing:

`lrunzip -K {{filename.lrz}}`

- Specify output file name and/or path:

`lrunzip -o {{outfilename}} {{filename.lrz}}`

