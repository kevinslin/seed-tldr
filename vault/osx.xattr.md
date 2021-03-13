---
id: osx.xattr
title: Xattr
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xattr

> Utility to work with extended filesystem attributes.

- List key:value extended attributes for a given file:

`xattr -l {{file}}`

- Write an attribute for a given file:

`xattr -w {{attribute_key}} {{attribute_value}} {{file}}`

- Delete an attribute from a given file:

`xattr -d {{com.apple.quarantine}} {{file}}`

- Delete all extended attributes from a given file:

`xattr -c {{file}}`

- Recursively delete an attribute in a given directory:

`xattr -rd {{attribute_key}} {{directory}}`

