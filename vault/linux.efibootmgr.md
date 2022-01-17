---
id: linux.efibootmgr
title: Efibootmgr
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# efibootmgr

> Manipulate the UEFI Boot Manager.
> More information: <https://manned.org/efibootmgr>.

- List the current settings / bootnums:

`efibootmgr`

- List the filepaths:

`efibootmgr -v`

- Add UEFI Shell v2 as a boot option:

`sudo efibootmgr -c -d {{/dev/sda1}} -l {{\EFI\tools\Shell.efi}} -L "{{UEFI Shell}}"`

- Change the current boot order:

`sudo efibootmgr -o {{0002,0008,0001,0005}}`

- Delete a boot option:

`sudo efibootmgr -b {{0008}} --delete-bootnum`

