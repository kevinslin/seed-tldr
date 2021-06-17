---
id: common.pio-update
title: Pio Update
desc: ''
updated: 1623965016144
created: 1623965016144
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio update

> Update installed PlatformIO Core packages, development platforms and global libraries.
> See also: `pio platform update`, `pio lib update`.
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_update.html>.

- Perform a full update of all packages, development platforms and global libraries:

`pio update`

- Update core packages only (skips platforms and libraries):

`pio update --core-packages`

- Check for new versions of packages, platforms and libraries but do not actually update them:

`pio update --dry-run`

