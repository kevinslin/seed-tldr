---
id: linux.mountpoint
title: Mountpoint
desc: ''
updated: 1615663978750
created: 1615663978750
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mountpoint

> Test if a directory is a filesystem mountpoint.

- Check if a directory is a mountpoint:

`mountpoint {{path/to/directory}}`

- Check if a directory is a mountpoint without showing any output:

`mountpoint -q {{path/to/directory}}`

- Show major/minor numbers of a mountpoint's filesystem:

`mountpoint --fs-devno {{path/to/directory}}`

