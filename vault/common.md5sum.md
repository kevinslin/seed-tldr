---
id: common.md5sum
title: Common
desc: ''
updated: 1615655543068
created: 1615655543068
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# md5sum

> Calculate MD5 cryptographic checksums.

- Calculate the MD5 checksum for a file:

`md5sum {{filename1}}`

- Calculate MD5 checksums for multiple files:

`md5sum {{filename1}} {{filename2}}`

- Read a file of MD5SUMs and verify all files have matching checksums:

`md5sum -c {{filename.md5}}`

- Calculate a MD5 checksum from the standard input:

`echo "{{text}}" | md5sum`

