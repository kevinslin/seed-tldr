---
id: linux.e2freefrag
title: E2freefrag
desc: ''
updated: 1615663978743
created: 1615663978743
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# e2freefrag

> Print the free space fragmentation information for ext2/ext3/ext4 filesystems.
> More information: <https://linux.die.net/man/8/e2freefrag>.

- Check how many free blocks are present as contiguous and aligned free space:

`e2freefrag {{/dev/sdXN}}`

- Specify chunk size in kilobytes to print how many free chunks are available:

`e2freefrag -c {{chunk_size_in_kb}} {{/dev/sdXN}}`

