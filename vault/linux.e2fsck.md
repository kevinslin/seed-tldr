---
id: linux.e2fsck
title: E2fsck
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
# e2fsck

> Check a Linux ext2/ext3/ext4 filesystem. The filesystem should be unmounted at the time the command is run.
> More information: <https://manned.org/e2fsck>.

- Check filesystem, reporting any damaged blocks:

`e2fsck {{/dev/sdXN}}`

- Check filesystem and automatically repair any damaged blocks:

`e2fsck -p {{/dev/sdXN}}`

- Check filesystem in read only mode:

`e2fsck -c {{/dev/sdXN}}`

