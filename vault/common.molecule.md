---
id: common.molecule
title: Molecule
desc: ''
updated: 1623965306197
created: 1623965306197
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

- Log in into the instance:

`molecule login`

