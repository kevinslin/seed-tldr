---
id: osx.md5
title: Osx
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# md5

> Calculate MD5 cryptographic checksums.

- Calculate the MD5 checksum for a file:

`md5 {{filename}}`

- Calculate MD5 checksums for multiple files:

`md5 {{filename1}} {{filename2}}`

- Output only the md5 checksum (no filename):

`md5 -q {{filename}}`

- Print a checksum of the given string:

`md5 -s {{string}}`

