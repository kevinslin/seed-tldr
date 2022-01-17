---
id: common.moe
title: Moe
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# moe

> A WYSIWYG text editor for ISO-8859-15 encoded text.
> More information: <https://www.gnu.org/software/moe/moe.html>.

- Open moe and create a backup file (file~) when saving edits:

`moe {{path/to/file}}`

- Open a file as read-only:

`moe --read-only {{path/to/file}}`

- Edit a file without creating backups:

`moe --no-backup {{path/to/file}}`

- Edit a file ignoring case in searches:

`moe --ignore-case {{path/to/file}}`

- Save and Quit:

`Ctrl + X`

