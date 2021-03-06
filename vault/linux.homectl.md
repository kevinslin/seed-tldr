---
id: linux.homectl
title: Homectl
desc: ''
updated: 1623965306223
created: 1623965306223
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# homectl

> Create, remove, change or inspect home directories using the systemd-homed service.
> More information: <https://man.archlinux.org/man/homectl.1>.

- List user accounts and their associated home directories:

`homectl list`

- Create a user account and their associated home directory:

`sudo homectl create {{username}}`

- Remove a specific user and the associated home directory:

`sudo homectl remove {{username}}`

- Change the password for a specific user:

`sudo homectl passwd {{username}}`

- Run a shell or a command with access to a specific home directory:

`sudo homectl with {{username}} -- {{command}} {{command_arguments}}`

- Lock or unlock a specific home directory:

`sudo homectl {{lock|unlock}} {{username}}`

- Change the disk space assigned to a specific home directory to 100 GiB:

`sudo homectl resize {{username}} {{100G}}`

- Display help:

`homectl --help`

