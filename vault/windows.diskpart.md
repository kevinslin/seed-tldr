---
id: windows.diskpart
title: Diskpart
desc: ''
updated: 1642441815127
created: 1642441815127
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diskpart

> Disk, volume and partition manager.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/diskpart>.

- Run diskpart by itself in an administrative command prompt to enter its command line:

`diskpart`

- List all disks:

`list disk`

- Select a volume:

`select volume {{volume}}`

- Assign a drive letter to the selected volume:

`assign letter {{letter}}`

- Create a new partition:

`create partition primary`

- Activate the selected volume:

`active`

- Exit diskpart:

`exit`

