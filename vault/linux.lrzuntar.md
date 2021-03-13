---
id: linux.lrzuntar
title: Lrzuntar
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lrzuntar

> A wrapper for `lrunzip` to simplify decompression of directories.
> See also: `lrztar`, `lrzip`.

- Decompress from a file to the current directory:

`lrzuntar {{path/to/archive.tar.lrz}}`

- Decompress from a file to the current directory using a specific number of processor threads:

`lrzuntar -p {{8}} {{path/to/archive.tar.lrz}}`

- Decompress from a file to the current directory and silently overwrite items that already exist:

`lrzuntar -f {{archive.tar.lrz}}`

- Specify the output path:

`lrzuntar -O {{path/to/directory}} {{archive.tar.lrz}}`

- Delete the compressed file after decompression:

`lrzuntar -D {{path/to/archive.tar.lrz}}`

