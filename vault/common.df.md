---
id: common.df
title: Df
desc: ''
updated: 1615663978705
created: 1615663978705
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# df

> Gives an overview of the filesystem disk space usage.

- Display all filesystems and their disk usage:

`df`

- Display all filesystems and their disk usage in human readable form:

`df -h`

- Display the filesystem and its disk usage containing the given file or directory:

`df {{path/to/file_or_directory}}`

- Display statistics on the number of free inodes:

`df -i`

- Display filesystems but exclude the specified type:

`df -x {{squashfs}} -x {{tmpfs}}`

