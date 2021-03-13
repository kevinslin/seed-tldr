---
id: common.odps-auth
title: Odps Auth
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# odps auth

> User authorities in ODPS (Open Data Processing Service).

- Add a user to the current project:

`add user {{username}};`

- Grant a set of authorities to a user:

`grant {{action_list}} on {{object_type}} {{object_name}} to user {{username}};`

- Show authorities of a user:

`show grants for {{username}};`

- Create a user role:

`create role {{role_name}};`

- Grant a set of authorities to a role:

`grant {{action_list}} on {{object_type}} {{object_name}} to role {{role_name}};`

- Describe authorities of a role:

`desc role {{role_name}};`

- Grant a role to a user:

`grant {{role_name}} to {{username}};`

