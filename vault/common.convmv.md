---
id: common.convmv
title: Convmv
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# convmv

> Convert filenames (NOT file content) from one encoding to another.
> More information: <https://www.j3e.de/linux/convmv/man/>.

- Test filename encoding conversion (don't actually change the filename):

`convmv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- Convert filename encoding and rename the file to the new encoding:

`convmv -f {{from_encoding}} -t {{to_encoding}} --notest {{input_file}}`

