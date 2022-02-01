---
id: linux.fossil-rm
title: Fossil Rm
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fossil rm

> Remove files or directories from Fossil version control.
> See also `fossil forget`.
> More information: <https://fossil-scm.org/home/help>.

- Remove a file or directory from Fossil version control:

`fossil rm {{path/to/file_or_directory}}`

- Remove a file or directory from Fossil version control, and also delete it from the disk:

`fossil rm --hard {{path/to/file_or_directory}}`

- Re-add all previously removed and uncommitted files to Fossil version control:

`fossil rm --reset`

