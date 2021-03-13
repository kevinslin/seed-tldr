---
id: common.iconv
title: Iconv
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# iconv

> Converts text from one encoding to another.

- Convert file to a specific encoding, and print to stdout:

`iconv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- Convert file to the current locale's encoding, and output to a file:

`iconv -f {{from_encoding}} {{input_file}} > {{output_file}}`

- List supported encodings:

`iconv -l`

