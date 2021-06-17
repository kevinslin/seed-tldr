---
id: common.git-check-attr
title: Git Check Attr
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git check-attr

> For every pathname, list if each attribute is unspecified, set, or unset as a gitattribute on that pathname.
> More information: <https://git-scm.com/docs/git-check-attr>.

- Check the values of all attributes on a file:

`git check-attr --all {{path/to/file}}`

- Check the value of a specific attribute on a file:

`git check-attr {{attribute}} {{path/to/file}}`

- Check the value of a specific attribute on files:

`git check-attr --all {{path/to/file1}} {{path/to/file2}}`

- Check the value of a specific attribute on one or more files:

`git check-attr {{attribute}} {{path/to/file1}} {{path/to/file2}}`

