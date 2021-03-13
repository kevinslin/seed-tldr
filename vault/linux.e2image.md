---
id: linux.e2image
title: E2image
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# e2image

> Save critical ext2/ext3/ext4 filesystem metadata to a file.
> More information: <https://linux.die.net/man/8/e2image>.

- Write metadata located on device to a specific file:

`e2image {{/dev/sdXN}} {{path/to/image_file}}`

- Print metadata located on device to stdout:

`e2image {{/dev/sdXN}} -`

- Restore the filesystem metadata back to the device:

`e2image -I {{/dev/sdXN}} {{path/to/image_file}}`

- Create a large raw sparse file with metadata at proper offsets:

`e2image -r {{/dev/sdXN}} {{path/to/image_file}}`

- Create a QCOW2 image file instead of a normal or raw image file:

`e2image -Q {{/dev/sdXN}} {{path/to/image_file}}`

