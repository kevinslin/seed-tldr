---
id: linux.timeshift
title: Timeshift
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# timeshift

> System restore utility.
> More information: <https://github.com/teejee2008/timeshift>.

- List snapshots:

`sudo timeshift --list`

- Create a new snapshot (if scheduled):

`sudo timeshift --check`

- Create a new snapshot (even if not scheduled):

`sudo timeshift --create`

- Restore a snapshot (selecting which snapshot to restore interactively):

`sudo timeshift --restore`

- Restore a specific snapshot:

`sudo timeshift --restore --snapshot '{{snapshot}}'`

- Delete a specific snapshot:

`sudo timeshift --delete --snapshot '{{snapshot}}'`

