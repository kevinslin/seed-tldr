---
id: common.git-show-index
title: Git Show Index
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git show-index

> Show the packed archive index of a Git repository.
> More information: <https://git-scm.com/docs/git-show-index>.

- Read an IDX file for a Git packfile and dump its contents to stdout:

`git show-index {{path/to/file.idx}}`

- Specify the hash algorithm for the index file (experimental):

`git show-index --object-format={{sha1|sha256}} {{path/to/file}}`

