---
id: common.mktemp
title: Mktemp
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mktemp

> Create a temporary file or directory.
> More information: <https://www.gnu.org/software/autogen/mktemp.html>.

- Create an empty temporary file and return the absolute path to it:

`mktemp`

- Create a temporary directory and return the absolute path to it:

`mktemp -d`

- Create a temporary file with a specified suffix:

`mktemp --suffix "{{.txt}}"`

