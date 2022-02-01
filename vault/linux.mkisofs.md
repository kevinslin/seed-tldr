---
id: linux.mkisofs
title: Mkisofs
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
# mkisofs

> Create ISO files from directories.
> Also aliased as `genisoimage`.
> More information: <https://manned.org/mkisofs>.

- Create an ISO from a directory:

`mkisofs -o {{filename.iso}} {{path/to/source_directory}}`

- Set the disc label when creating an ISO:

`mkisofs -o {{filename.iso}} -V "{{label_name}}" {{path/to/source_directory}}`

