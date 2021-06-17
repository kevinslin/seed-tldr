---
id: osx.oathtool
title: Oathtool
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# oathtool

> OATH one-time password tool.

- Generate TOTP token (behaves like Google Authenticator):

`oathtool --totp --base32 {{secret}}`

- Generate a TOTP token for a specific time:

`oathtool --totp --now {{2004-02-29 16:21:42}} --base32 {{secret}}`

- Validate a TOTP token:

`oathtool --totp --base32 {{secret}} {{token}}`

