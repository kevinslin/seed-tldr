---
id: common.ln
title: Ln
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ln

> Creates links to files and directories.
> More information: <https://www.gnu.org/software/coreutils/ln>.

- Create a symbolic link to a file or directory:

`ln -s {{/path/to/file_or_directory}} {{path/to/symlink}}`

- Overwrite an existing symbolic link to point to a different file:

`ln -sf {{/path/to/new_file}} {{path/to/symlink}}`

- Create a hard link to a file:

`ln {{/path/to/file}} {{path/to/hardlink}}`

