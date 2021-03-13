---
id: osx.codesign
title: Codesign
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# codesign

> Create and manipulate code signatures for macOS.

- Sign an application with a certificate:

`codesign -s "{{My Company Name}}" {{path/to/App.app}}`

- Verify the certificate of an application:

`codesign -v {{path/to/App.app}}`

