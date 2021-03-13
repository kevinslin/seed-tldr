---
id: windows.chkdsk
title: Chkdsk
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# chkdsk

> Check file system and volume metadata for errors.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/chkdsk>.

- Specify the drive letter (followed by a colon), mount point, or volume name to check:

`chkdsk {{volume}}`

- Fix errors on a specific volume:

`chkdsk {{volume}} /f`

- Dismount a specific volume before checking:

`chkdsk {{volume}} /x`

- Change the log file size to the specified size (only for NTFS):

`chkdsk /l{{size}}`

