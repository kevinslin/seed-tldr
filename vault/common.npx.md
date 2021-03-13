---
id: common.npx
title: Npx
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# npx

> Execute binaries from `npm` packages.
> More information: <https://www.npmjs.com/package/npx>.

- Execute the binary from a given npm module:

`npx {{module_name}}`

- In case a package has multiple binaries, specify the package name along with the binary:

`npx -p {{package_name}} {{module_name}}`

- View help contents:

`npx --help`

