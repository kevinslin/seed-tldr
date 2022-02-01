---
id: linux.edit
title: Edit
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# edit

> An alias to a `run-mailcap`'s action edit.
> Originally `run-mailcap` is used to process/edit mime-type/file.
> More information: <https://www.computerhope.com/unix/uedit.htm>.

- Edit action can be used to view any file on default mailcap explorer:

`edit {{filename}}`

- With `run-mailcap`:

`run-mailcap --action=edit {{filename}}`

