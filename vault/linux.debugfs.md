---
id: linux.debugfs
title: Debugfs
desc: ''
updated: 1623965306221
created: 1623965306221
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# debugfs

> An interactive ext2/ext3/ext4 filesystem debugger.

- Open the filesystem in read only mode:

`debugfs {{/dev/sdXN}}`

- Open the filesystem in read write mode:

`debugfs -w {{/dev/sdXN}}`

- Read commands from a specified file, execute them and then exit:

`debugfs -f {{path/to/cmd_file}} {{/dev/sdXN}}`

- View the filesystem stats in debugfs console:

`stats`

- Close the filesystem:

`close -a`

- List all available commands:

`lr`

