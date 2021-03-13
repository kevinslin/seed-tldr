---
id: common.ect
title: Ect
desc: ''
updated: 1615655543053
created: 1615655543053
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ect

> Efficient Compression Tool (or ECT) is a C++ file optimizer. It supports PNG, JPEG, GZIP and ZIP files.
> More information: <https://github.com/fhanau/Efficient-Compression-Tool>.

- Compress a file:

`ect {{filename.png}}`

- Compress a file with the highest compression level and multithreading:

`ect -9 --mt-deflate {{filename.png}}`

- Compress all the files in a directory recursively, keeping the original modification time:

`ect -keep -recurse {{directory}}`

