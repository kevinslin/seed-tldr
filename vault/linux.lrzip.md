---
id: linux.lrzip
title: Lrzip
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lrzip

> A large file compression program.
> See also `lrunzip`, `lrztar`, `lrzuntar`.

- Compress a file with LZMA - slow compression, fast decompression:

`lrzip {{filename}}`

- Compress a file with BZIP2 - good middle ground for compression/speed:

`lrzip -b {{filename}}`

- Compress with ZPAQ - extreme compression, but very slow:

`lrzip -z {{filename}}`

- Compress with LZO - light compression, extremely fast decompression:

`lrzip -l {{filename}}`

- Compress a file and password protect/encrypt it:

`lrzip -e {{filename}}`

- Override the number of processor threads to use:

`lrzip -p {{8}} {{filename}}`

