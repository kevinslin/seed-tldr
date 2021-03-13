---
id: linux.debugfs
title: Debugfs
desc: ''
updated: 1615655543097
created: 1615655543097
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

