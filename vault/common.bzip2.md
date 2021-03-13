---
id: common.bzip2
title: Bzip2
desc: ''
updated: 1615655543047
created: 1615655543047
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# bzip2

> A block-sorting file compressor.
> More information: <http://bzip.org>.

- Compress a file:

`bzip2 {{path/to/file_to_compress}}`

- Decompress a file:

`bzip2 -d {{path/to/compressed_file.bz2}}`

- Decompress a file to standard output:

`bzip2 -dc {{path/to/compressed_file.bz2}}`

