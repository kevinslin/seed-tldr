---
id: osx.dd
title: Dd
desc: ''
updated: 1642441815120
created: 1642441815120
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dd

> Convert and copy a file.
> More information: <https://ss64.com/osx/dd.html>.

- Make a bootable USB drive from an isohybrid file (such like `archlinux-xxx.iso`):

`dd if={{file.iso}} of=/dev/{{usb_drive}}`

- Clone a drive to another drive with 4 MB block and ignore error:

`dd if=/dev/{{source_drive}} of=/dev/{{dest_drive}} bs=4m conv=noerror`

- Generate a file of 100 random bytes by using kernel random driver:

`dd if=/dev/urandom of={{random_file}} bs=100 count=1`

- Benchmark the write performance of a disk:

`dd if=/dev/zero of={{file_1GB}} bs=1024 count=1000000`

