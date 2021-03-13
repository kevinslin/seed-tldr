---
id: common.nrm
title: Nrm
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nrm

> NPM registry manager.
> Helps to easily switch between different npm registries.
> More information: <https://github.com/Pana/nrm>.

- List all registries:

`nrm ls`

- Change to a particular registry:

`nrm use {{registry}}`

- Show the response time for all registries:

`nrm test`

- Add a custom registry:

`nrm add {{registry}} {{url}}`

- Delete a registry:

`nrm del {{registry}}`

