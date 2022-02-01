---
id: linux.mkswap
title: Mkswap
desc: ''
updated: 1642441815104
created: 1642441815104
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkswap

> Sets up a Linux swap area on a device or in a file.
> More information: <https://manned.org/mkswap>.

- Setup a given partition as swap area:

`sudo mkswap {{/dev/sdb7}}`

- Use a given file as swap area:

`sudo mkswap {{path/to/file}}`

- Check a partition for bad blocks before creating the swap area:

`sudo mkswap -c {{/dev/sdb7}}`

- Specify a label for the file (to allow `swapon` to use the label):

`sudo mkswap -L {{swap1}} {{path/to/file}}`

