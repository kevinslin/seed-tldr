---
id: common.enca
title: Enca
desc: ''
updated: 1615655543053
created: 1615655543053
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# enca

> Detect and convert the encoding of text files.
> More information: <https://github.com/nijel/enca>.

- Detect file(s) encoding according to the system's locale:

`enca {{file1 file2 ...}}`

- Detect file(s) encoding specifying a language in the POSIX/C locale format (e.g. zh_CN, en_US):

`enca -L {{language}} {{file1 file2 ...}}`

- Convert file(s) to a specific encoding:

`enca -L {{language}} -x {{to_encoding}} {{file1 file2 ...}}`

- Create a copy of an existing file using a different encoding:

`enca -L {{language}} -x {{to_encoding}} < {{original_file}} > {{new_file}}`

