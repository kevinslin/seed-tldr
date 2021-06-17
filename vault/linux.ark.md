---
id: linux.ark
title: Ark
desc: ''
updated: 1623965306219
created: 1623965306219
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ark

> KDE archiving tool.
> More information: <https://docs.kde.org/stable5/en/kdeutils/ark/>.

- Extract an archive into the current directory:

`ark --batch {{archive}}`

- Change extraction directory:

`ark --batch --destination {{path/to/directory}} {{archive}}`

- Create an archive if it does not exist and add files to it:

`ark --add-to {{archive}} {{file1}} {{file2}}`

