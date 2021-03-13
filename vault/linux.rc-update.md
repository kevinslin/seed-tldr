---
id: linux.rc-update
title: Rc Update
desc: ''
updated: 1615655543108
created: 1615655543108
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rc-update

> Add and remove OpenRC services to and from runlevels.
> See also `openrc`.

- List all services and the runlevels they are added to:

`rc-update show`

- Add a service to a runlevel:

`sudo rc-update add {{service_name}} {{runlevel}}`

- Delete a service from a runlevel:

`sudo rc-update delete {{service_name}} {{runlevel}}`

- Delete a service from all runlevels:

`sudo rc-update --all delete {{service_name}}`

