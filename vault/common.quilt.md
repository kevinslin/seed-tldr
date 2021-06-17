---
id: common.quilt
title: Quilt
desc: ''
updated: 1623965016146
created: 1623965016146
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# quilt

> Tool to manage a series of patches.
> More information: <https://savannah.nongnu.org/projects/quilt>.

- Import an existing patch from a file:

`quilt import {{path/to/filename.patch}}`

- Create a new patch:

`quilt new {{filename.patch}}`

- Add a file to the current patch:

`quilt add {{path/to/file}}`

- After editing the file, refresh the current patch with the changes:

`quilt refresh`

- Apply all the patches in the series file:

`quilt push -a`

- Remove all applied patches:

`quilt pop -a`

