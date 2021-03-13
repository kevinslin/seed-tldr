---
id: common.odps-resource
title: Odps Resource
desc: ''
updated: 1615655543076
created: 1615655543076
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# odps resource

> Manage resources in ODPS (Open Data Processing Service).

- Show resources in the current project:

`list resources;`

- Add file resource:

`add file {{filename}} as {{alias}};`

- Add archive resource:

`add archive {{archive.tar.gz}} as {{alias}};`

- Add .jar resource:

`add jar {{package.jar}};`

- Add .py resource:

`add py {{script.py}};`

- Delete resource:

`drop resource {{resource_name}};`

