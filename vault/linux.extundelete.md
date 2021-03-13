---
id: linux.extundelete
title: Extundelete
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# extundelete

> Recover deleted files from ext3 or ext4 partitions by parsing the journal.
> See also `date` for Unix time information and `umount` for unmounting partitions.
> More information: <http://extundelete.sourceforge.net>.

- Restore all deleted files inside partition N on device X:

`sudo extundelete {{/dev/sdXN}} --restore-all`

- Restore a file from a path relative to root (Do not start the path with `/`):

`extundelete {{/dev/sdXN}} --restore-file {{path/to/file}}`

- Restore a directory from a path relative to root (Do not start the path with `/`):

`extundelete {{/dev/sdXN}} --restore-directory {{path/to/directory}}`

- Restore all files deleted after January 1st, 2020 (in Unix time):

`extundelete {{/dev/sdXN}} --restore-all --after {{1577840400}}`

