---
id: linux.rmmod
title: Rmmod
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmmod

> Remove modules from the Linux kernel.
> More information: <https://manned.org/rmmod>.

- Remove a module from the kernel:

`sudo rmmob {{module_name}}`

- Remove a module from the kernel and display verbose information:

`sudo rmmob --verbose {{module_name}}`

- Remove a module from the kernel and send errors to syslog instead of standard error:

`sudo rmmob --syslog {{module_name}}`

- Display help:

`rmmob --help`

- Display version:

`rmmob --version`

