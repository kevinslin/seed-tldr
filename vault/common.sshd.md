---
id: common.sshd
title: Sshd
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sshd

> Secure Shell Daemon - allows remote machines to securely log in to the current machine.
> Remote machines can execute commands as it is executed at this machine.
> More information: <https://man.openbsd.org/sshd>.

- Start daemon in the background:

`sshd`

- Run sshd in the foreground:

`sshd -D`

- Run with verbose output (for debugging):

`sshd -D -d`

- Run on a specific port:

`sshd -p {{port}}`

