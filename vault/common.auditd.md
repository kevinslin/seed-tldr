---
id: common.auditd
title: Auditd
desc: ''
updated: 1642441814995
created: 1642441814995
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# auditd

> This responds to requests from the audit utility and notifications from the kernel.
> It should not be invoked manually.
> More information: <https://manned.org/auditd>.

- Start the daemon:

`auditd`

- Start the daemon in debug mode:

`auditd -d`

- Start the daemon on-demand from launchd:

`auditd -l`

