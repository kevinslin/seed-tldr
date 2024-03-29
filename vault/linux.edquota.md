---
id: linux.edquota
title: Edquota
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# edquota

> Edit quotas for a user or group. By default it operates on all filesystems with quotas.
> Quota information is stored permanently in the `quota.user` and `quota.group` files in the root of the filesystem.
> More information: <https://manned.org/edquota>.

- Edit quota of the current user:

`edquota --user $(whoami)`

- Edit quota of a specific user:

`sudo edquota --user {{username}}`

- Edit quota for a group:

`sudo edquota --group {{group}}`

- Restrict operations to a given filesystem (by default edquota operates on all filesystems with quotas):

`sudo edquota --file-system {{filesystem}}`

- Edit the default grace period:

`sudo edquota -t`

- Duplicate a quota to other users:

`sudo edquota -p {{reference_user}} {{destination_user1}} {{destination_user2}}`

