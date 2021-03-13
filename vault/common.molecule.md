---
id: common.molecule
title: Molecule
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# molecule

> Molecule helps testing ansible roles.
> More information: <https://molecule.readthedocs.io>.

- Create a new ansible role:

`molecule init role --role-name {{role_name}}`

- Run tests:

`molecule test`

- Start the instance:

`molecule create`

- Configure the instance:

`molecule converge`

- Login into the instance:

`molecule login`

