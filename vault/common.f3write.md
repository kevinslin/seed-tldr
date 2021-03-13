---
id: common.f3write
title: F3write
desc: ''
updated: 1615655543054
created: 1615655543054
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# f3write

> Fill a drive out with .h2w files to test its real capacity.
> See also `f3read`, `f3probe`, `f3fix`.
> More information: <http://oss.digirati.com.br/f3/>.

- Write test files to a given directory, filling the drive:

`f3write {{path/to/mount_point}}`

- Limit the write speed:

`f3write --max-write-rate={{kb_per_second}} {{path/to/mount_point}}`

