---
id: common.rmdir
title: Rmdir
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmdir

> Removes a directory.
> More information: <https://www.gnu.org/software/coreutils/rmdir>.

- Remove directory, provided it is empty. Use `rm -r` to remove non-empty directories:

`rmdir {{path/to/directory}}`

- Remove the target and its parent directories (useful for nested dirs):

`rmdir -p {{path/to/directory}}`

