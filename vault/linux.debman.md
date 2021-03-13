---
id: linux.debman
title: Debman
desc: ''
updated: 1615655543097
created: 1615655543097
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# debman

> Read man pages from uninstalled packages.

- Read a man page for a command that is provided by a specified package name:

`debman -p {{package_name}} {{command_name}}`

- Specify a package version to download:

`debman -p {{package_name}}={{version}} {{command_name}}`

- Read a man page in a `.deb` file:

`debman -f {{path/to/filename.deb}} {{command_name}}`

