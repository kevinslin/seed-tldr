---
id: common.makensis
title: Makensis
desc: ''
updated: 1615655543068
created: 1615655543068
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# makensis

> Cross-platform compiler for NSIS installers.
> It compiles a NSIS script into a Windows installer executable.
> More information: <https://nsis.sourceforge.io/Docs/Chapter3.html>.

- Compile a NSIS script:

`makensis {{path/to/file.nsi}}`

- Compile a NSIS script in strict mode (treat warnings as errors):

`makensis -WX {{path/to/file.nsi}}`

- Print help for a specific command:

`makensis -CMDHELP {{command}}`

