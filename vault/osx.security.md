---
id: osx.security
title: Security
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# security

> Administer Keychains, keys, certificates and the Security framework.
> More information: <https://ss64.com/osx/security.html>.

- List the available keychains:

`security list-keychains`

- Delete a specific keychain:

`security delete-keychain {{path}}`

- Create a keychain:

`security create-keychain -p {{password}} {{name.keychain}}`

