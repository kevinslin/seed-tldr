---
id: linux.wipefs
title: Wipefs
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wipefs

> Wipe filesystem, raid, or partition-table signatures from a device.

- Display signatures for specified device:

`sudo wipefs {{/dev/sdX}}`

- Wipe all available signatures for specified device:

`sudo wipefs --all {{/dev/sdX}}`

- Perform dry run:

`sudo wipefs --all --no-act {{/dev/sdX}}`

- Force wipe, even if the filesystem is mounted:

`sudo wipefs --all --force {{/dev/sdX}}`

