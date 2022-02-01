---
id: common.pio-system
title: Pio System
desc: ''
updated: 1642441815059
created: 1642441815059
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio system

> Miscellaneous system commands for PlatformIO.
> More information: <https://docs.platformio.org/en/latest/core/userguide/system/>.

- Install shell completion for the current shell (supports Bash, Fish, Zsh and PowerShell):

`pio system completion install`

- Uninstall shell completion for the current shell:

`pio system completion uninstall`

- Display system-wide PlatformIO information:

`pio system info`

- Remove unused PlatformIO data:

`pio system prune`

- Remove only cached data:

`pio system prune --cache`

- List unused PlatformIO data that would be removed but do not actually remove it:

`pio system prune --dry-run`

