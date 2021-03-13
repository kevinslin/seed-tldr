---
id: linux.nsenter
title: Nsenter
desc: ''
updated: 1615655543106
created: 1615655543106
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nsenter

> Run a new command in a running process' namespace.
> Particularly useful for docker images or chroot jails.
> More information: <https://github.com/jpetazzo/nsenter/>.

- Run command in existing processes network namespace:

`nsenter -t {{pid}} -n {{command}} {{command_arguments}}`

- Run a new command in an existing processes ps-table namespace:

`nsenter -t {{pid}} -p {{command}} {{command_arguments}}`

- Run command in existing processes IPC namespace:

`nsenter -t {{pid}} -i {{command}} {{command_arguments}}`

