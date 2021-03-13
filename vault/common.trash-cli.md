---
id: common.trash-cli
title: Trash CLI
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# trash-cli

> A command line interface to the trashcan APIs.
> More information: <https://github.com/andreafrancia/trash-cli>.

- Trash files and directories:

`trash-put {{filename}}`

- Empty the trashcan:

`trash-empty`

- List trashed files:

`trash-list`

- Restore a trashed file by choosing a number from the list that results from this command:

`trash-restore`

- Remove individual files from the trashcan:

`trash-rm {{filename}}`

