---
id: common.quota
title: Quota
desc: ''
updated: 1623965306207
created: 1623965306207
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# quota

> Display users' disk space usage and allocated limits.

- Show disk quotas in human readable units for the current user:

`quota -s`

- Verbose output (also display quotas on filesystems where no storage is allocated):

`quota -v`

- Quiet output (only display quotas on filesystems where usage is over quota):

`quota -q`

- Print quotas for the groups of which the current user is a member:

`quota -g`

- Show disk quotas for another user:

`sudo quota -u {{username}}`

