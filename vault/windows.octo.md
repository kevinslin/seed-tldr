---
id: windows.octo
title: Octo
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# octo

> Command line tools for Octopus Deploy.
> More information: <https://octopus.com/docs/octopus-rest-api/octo.exe-command-line>.

- Create a package:

`octo pack --id={{package_name}}`

- Push a package to a repository on the Octopus server:

`octo push --package={{package_name}}`

- Create a release:

`octo create-release --project={{project_name}} --packageversion={{version}}`

- Deploy a release:

`octo deploy-release --project={{project_name}} --packageversion={{version}} --deployto={{environment_name}} --tenant={{deployment_target}}`

