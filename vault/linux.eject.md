---
id: linux.eject
title: Eject
desc: ''
updated: 1615663978745
created: 1615663978745
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eject

> Eject cds, floppy disks and tape drives.

- Display the default device:

`eject -d`

- Eject the default device:

`eject`

- Eject a specific device (the default order is cd-rom, scsi, floppy and tape):

`eject {{/dev/cdrom}}`

- Toggle whether a device's tray is open or closed:

`eject -T {{/dev/cdrom}}`

- Eject a cd drive:

`eject -r {{/dev/cdrom}}`

- Eject a floppy drive:

`eject -f {{/mnt/floppy}}`

- Eject a tape drive:

`eject -q {{/mnt/tape}}`

