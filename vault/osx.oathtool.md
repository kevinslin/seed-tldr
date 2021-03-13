---
id: osx.oathtool
title: Oathtool
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# oathtool

> OATH one-time password tool.

- Generate TOTP token (behaves like Google Authenticator):

`oathtool --totp --base32 {{secret}}`

- Generate a TOTP token for a specific time:

`oathtool --totp --now {{2004-02-29 16:21:42}} --base32 {{secret}}`

- Validate a TOTP token:

`oathtool --totp --base32 {{secret}} {{token}}`

