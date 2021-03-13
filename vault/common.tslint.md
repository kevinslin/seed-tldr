---
id: common.tslint
title: Tslint
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# tslint

> A pluggable linting utility for TypeScript.
> More information: <https://palantir.github.io/tslint>.

- Create tslint config:

`tslint --init`

- Lint on a given set of files:

`tslint {{filename}}.js {{filename1}}.js`

- Fix lint issues:

`tslint --fix`

- Lint with the config file in the project root:

`tslint --project {{path/to/project_root}}`

