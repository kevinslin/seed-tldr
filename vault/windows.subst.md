---
id: windows.subst
title: Subst
desc: ''
updated: 1615663978764
created: 1615663978764
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# subst

> Associates a path with a virtual drive letter.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/subst>.

- List active associations:

`subst`

- Add an association:

`subst {{Z:}} {{C:\Python2.7}}`

- Remove an association:

`subst {{Z:}} /d`
