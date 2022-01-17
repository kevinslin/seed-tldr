---
id: osx.fsck
title: Fsck
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fsck

> Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run.
> It is a wrapper that calls `fsck_hfs`, `fsck_apfs`, `fsck_msdos`, `fsck_exfat`, and `fsck_udf` as needed.
> More information: <https://ss64.com/osx/fsck.html>.

- Check filesystem `/dev/sdX`, reporting any damaged blocks:

`fsck {{/dev/sdX}}`

- Check filesystem `/dev/sdX` only if it is clean, reporting any damaged blocks and interactively letting the user choose to repair each one:

`fsck -f {{/dev/sdX}}`

- Check filesystem `/dev/sdX` only if it is clean, reporting any damaged blocks and automatically repairing them:

`fsck -fy {{/dev/sdX}}`

- Check filesystem `/dev/sdX`, reporting whether it has been cleanly unmounted:

`fsck -q {{/dev/sdX}}`

