---
id: common.sync
title: Sync
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sync

> Flushes all pending write operations to the appropriate disks.
> More information: <https://www.gnu.org/software/coreutils/sync>.

- Flush all pending write operations on all disks:

`sync`

- Flush all pending write operations on a single file to disk:

`sync {{path/to/file}}`

