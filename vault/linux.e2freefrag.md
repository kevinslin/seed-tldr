---
id: linux.e2freefrag
title: E2freefrag
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# e2freefrag

> Print the free space fragmentation information for ext2/ext3/ext4 filesystems.
> More information: <https://linux.die.net/man/8/e2freefrag>.

- Check how many free blocks are present as contiguous and aligned free space:

`e2freefrag {{/dev/sdXN}}`

- Specify chunk size in kilobytes to print how many free chunks are available:

`e2freefrag -c {{chunk_size_in_kb}} {{/dev/sdXN}}`

