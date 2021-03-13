---
id: linux.nsenter
title: Nsenter
desc: ''
updated: 1615663978751
created: 1615663978751
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

